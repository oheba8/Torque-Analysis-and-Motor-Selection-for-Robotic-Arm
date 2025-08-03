# Torque-Analysis-and-Motor-Selection-for-Robotic-Arm

Overview
This project involves calculating the required torque at each joint of a robotic arm based on the payload, and selecting suitable servo motors accordingly. It also explores the possibility of increasing the payload from 1 kg to 2 kg using the same motors combined with gearboxes. Additionally, it discusses the limitations of this approach and suggests alternative design improvements.

Torque Calculation Method
The torque required at each joint is computed using the formula:


Torque (N\cdotpm)=Mass (kg)×9.81×Distance (m)
Where:

Mass is the weight being supported at that joint,

Distance is the length from the joint axis to the load center.

Estimated Torques for 1 kg Payload:
Joint 3 (Gripper): approx. 0.4 N·m

Joint 2 (Middle Arm): approx. 1.4 N·m

Joint 1 (Base): approx. 8.5 N·m

Selected Motors
Joint 3:

Model: GoolRC 80 kg High Torque Digital Servo

Stall Torque: ~105 kg·cm (≈10.5 N·m)

Link:[ Amazon
](https://www.amazon.sa/dp/B0B5H3YYQX?ref=cm_sw_r_cso_cp_apin_dp_35YJKVM5435YQWN8TNKD_1&ref_=cm_sw_r_cso_cp_apin_dp_35YJKVM5435YQWN8TNKD_1&social_share=cm_sw_r_cso_cp_apin_dp_35YJKVM5435YQWN8TNKD_1)
Joint 2:

Model: DS3235 35 kg High Torque Servo

Stall Torque: ~35 kg·cm (≈3.5 N·m)

Link:[ Amazon](https://www.amazon.sa/dp/B0CJFR6KV9?ref=cm_sw_r_cso_cp_apin_dp_DCNBKPVMS7TQ668E96MN&ref_=cm_sw_r_cso_cp_apin_dp_DCNBKPVMS7TQ668E96MN&social_share=cm_sw_r_cso_cp_apin_dp_DCNBKPVMS7TQ668E96MN&th=1)

Joint 1:

Model: High Torque Servo Motor (Continuous Torque: 10 N·m)

Stall Torque: 10 N·m

Link: [Amazon](https://www.amazon.sa/dp/B09JWK494C?ref=cm_sw_r_cso_cp_mwn_dp_ZF89JFM462X203W5RGVD_1&ref_=cm_sw_r_cso_cp_mwn_dp_ZF89JFM462X203W5RGVD_1&social_share=cm_sw_r_cso_cp_mwn_dp_ZF89JFM462X203W5RGVD_1)

Payload Upgrade to 2 kg
Doubling the payload to 2 kg nearly doubles the torque required at each joint:

Joint 3: approx. 0.8 N·m

Joint 2: approx. 2.8 N·m

Joint 1: approx. 11.4 N·m

Can the Existing Motors Handle It?
Yes, but only if paired with planetary gearboxes to amplify torque output.

Gearboxes trade off speed for increased torque.

Drawbacks of This Approach
Lower overall movement speed

Increased power consumption

Greater risk of overheating

More mechanical stress on joints and structure

Alternative Improvements
Use lighter materials for the robotic arm

Shorten arm segments to reduce torque requirements

Upgrade to higher torque industrial-grade servos

Integrate torque-optimized gearboxes

Notes
All torque calculations assume standard gravitational acceleration (9.81 m/s²).

A safety margin is maintained in motor selection to ensure reliability.

Motor links are provided for reference and sourcing purposes.
