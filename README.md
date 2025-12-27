# UMOD-dataset
Collected via an ROV platform, this first public underwater vision-sonar dataset features nine static and dynamic targets. Sensor data from a BlueView M900 sonar and ZED2 camera enables research in cross-modal detection, tracking, and feature matching.

<img width="1357" height="219" alt="数据集样例图" src="https://github.com/user-attachments/assets/b79ced07-e166-4563-bbef-9986a98597b4" />

```mermaid
graph TD
    UMOD[UMOD/] --> Vis[Vis/]
    Vis --> Vis_imgs[imgs/]
    Vis --> Vis_labels[labels/]
    UMOD --> Sonar[Sonar/]
    Sonar --> Sonar_imgs[imgs/]
    Sonar --> Sonar_labels[labels/]

At the same time, we also offer the download method via Baidu Cloud Drive: https://pan.baidu.com/s/1U_EaPCkYJ7Mp-ZymB5Wnsw?pwd=dsqi ; Extract code: dsqi 

Different formats of annotations will be updated later.......
