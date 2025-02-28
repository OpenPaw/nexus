# Nexus 
🤖 Nexus is robot software for use on a simple Pi or other GPIO-based system. It is made possible with the assistance of an LLM (large language model) like LLaMA 3.2.

## `🛜` Network
1) It communicates to a remote and central AI server on **your** network (for low-latency communication), `https://robot.local` for example.
2) The central AI server identifies your robot and places it inside it's hub for management.
3) The central AI server communicates with the robot through HTTP securely (authorization secure).
4) Your robot receives requests and sends requests, helping things like speech data reach the central AI server.

## `📖` Features
- `👁️` It uses YOLOv8 software to detect objects out of a camera
- `🦾` It uses OpenPaw software as a proxy
- `🖥️` Requires a local machine (a good control station) that can run large language models efficiently, otherwise it will be super slow
- `⏰` Completely real-time (*unless your network is slow, minimum Wi-Fi 4 or 5-gigabit Ethernet connection recommended)

## `🤔` Considerations
- It is recommended that you get a GPU that can run both of these models efficiently and effectively. Aim for a GPU that has at least 12GB of VRAM and a lot of CUDA cores for your OpenPaw server software.

## `👤` Contributors
No contributors yet.
