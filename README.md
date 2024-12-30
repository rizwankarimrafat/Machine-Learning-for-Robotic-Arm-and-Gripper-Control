# Machine Learning for Robotic Arm and Gripper Control

This project explores advanced machine learning techniques for robotic grasping in unstructured environments. The focus is on the implementation and evaluation of the Learning to Grasp (L2G) model, a 6-DOF grasp prediction framework that processes 3D point cloud data to identify stable grasp points. This work emphasizes the importance of adaptability and precision in robotic manipulation, particularly for diverse and unpredictable scenarios.

## Watch the Project Demo

[![Watch the video](https://img.youtube.com/vi/_jLn-Lp1rbQ/0.jpg)](https://www.youtube.com/watch?v=_jLn-Lp1rbQ)

https://www.youtube.com/watch?v=_jLn-Lp1rbQ

Click the thumbnail above to watch a detailed video demonstration of the project's simulations and real-world deployment attempts.

# Key Highlights

1. **Simulation-Based Validation:** The L2G model was tested extensively in simulation using datasets like ShapeNetSem-8 and YCB-76. Results demonstrated a high grasp success rate (93.6% for top 10% predictions) and superior inference times compared to baseline models such as GPNet. The model's differentiable sampling method and robust feature extraction techniques contributed to its strong performance in both prediction accuracy and efficiency.

2. **Real-World Deployment Challenges:** Efforts to deploy the L2G model on the Doosan A0509 robotic arm faced technical barriers. Network connectivity issues, hardware limitations, and software compatibility challenges hindered seamless integration. These findings highlight the complexities of transitioning from simulation to real-world applications and underscore the need for robust infrastructure and cohesive control systems.

3. **Future Directions:** Enhancements such as integrating 3D perception technologies (e.g., depth or stereo cameras) and testing on alternative robotic platforms like the Franka Emika Panda are recommended. These advancements would improve the model’s generalizability and effectiveness in diverse environments, paving the way for broader adoption in industries like logistics, healthcare, and home automation.

# Conclusion

This project validates the potential of machine learning models like L2G for robotic grasping tasks in dynamic and unstructured settings. While simulation results underscore the model’s robustness and accuracy, real-world deployment challenges reveal critical areas for improvement. Future work will focus on enhancing perception capabilities, addressing infrastructure limitations, and expanding applicability across multiple robotic systems.
