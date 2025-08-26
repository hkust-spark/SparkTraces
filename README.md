# SparkTraces

This repository contains a dataset of network traces collected from various sources, including 4G, WiFi, Ethernet from Tencent, Alibaba, and the FCC. The dataset is designed to facilitate research in network performance, adaptive bitrate algorithms, and real-time communications.

## Dataset Description

The dataset includes traces that are formatted as follows:

- **General Format**:
  `timestamp(s) bandwidth(Mbps)`

- **Hairpin Traces Format**:
  `timestamp(s) bandwidth(Mbps) RTT(ms) Loss rate`

### Papers Referenced

This dataset is associated with the following research papers:

1. **PiTree**
   - **Paper**: [Practically deploying heavyweight adaptive bitrate algorithms with teacher-student learning](https://ieeexplore.ieee.org/document/9334431)
   - **Dataset Description**: [PiTree Dataset](https://newtrip-project.github.io/pitree-dataset/traces/index.html)

2. **Zhuge**
   - **Paper**: [Achieving Consistent Low Latency for Wireless Real-Time Communications with the Shortest Control Loop](https://dl.acm.org/doi/10.1145/3544216.3544225)

3. **Hairpin**
   - **Paper**: [Hairpin: Rethinking Packet Loss Recovery in Edge-based Interactive Video Streaming](https://www.usenix.org/conference/nsdi24/presentation/meng)

## Dataset Collection Methodology

To ensure there is no bias towards any specific dataset or type, we have randomly selected an equal overall duration of each type in the dataset. The overall duration for each type is set to **4500 seconds**.

## Usage

Feel free to use this dataset for your research purposes. If you have any questions or need further information, please contact the repository maintainer.

## License

This dataset is provided for research purposes. Please cite the associated papers if you use this dataset in your work.