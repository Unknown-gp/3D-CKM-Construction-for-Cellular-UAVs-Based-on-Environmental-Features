# 3D-CKM-Construction-for-Cellular-UAVs-Based-on-Environmental-Features
3D CKM Construction for Cellular-UAVs Based on Environmental Features
Abstract—Cellular-connected unmanned aerial vehicle (UAV)
communication faces challenges such as rapidly time-varying
channels, dynamic blockages, and Doppler effects in low-altitude
applications. Accurate and rapid channel prediction is crucial for
ensuring communication reliability. As a potential technology that
can enhance communication performance, channel knowledge
maps (CKM) can provide channel status information (CSI) at
specific locations for UAV wireless communications. However,
traditional construction schemes based on measurements, ray
tracing (RT), or historical CSI often fail to adequately consider
the impact of environmental features (such as building layout and
height), and still exhibit significant limitations in constructing
three-dimensional (3D) CKMs for low-altitude urban environments with dense buildings. In this paper, we propose a deep
learning network architecture named MPANet, which effectively
addresses the challenge of 3D spatial CKM construction. The
model not only integrates complex environmental features from
height-preserving 2D images but also utilizes dual attention
mechanisms to focus on key regions across both channel and
spatial dimensions. This enables joint multi-altitude path loss
prediction in low-altitude environments and generates 3D path
loss distributions based on environmental characteristics, offering
a novel solution for constructing CKMs for cellular-connected
UAVs. Results demonstrate that our proposed method delivers
high-precision signal path loss prediction for UAV communications. MPANet achieves a root mean square error (RMSE) below
0.2 dB across all test scenarios, exhibiting superior performance
compared to traditional construction approaches.
Index Terms—UAV cellular communication, channel knowledge map, path loss prediction, deep learning