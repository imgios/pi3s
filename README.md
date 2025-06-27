<h3 align="center">
    <img src="https://i.ibb.co/HLjFmxb1/pie.png" alt="pie" border="0"><br/>
    <code>pi3s</code>
</h3>

Mono repository for the <kbd>LAG Cloud</kbd>'s edge cluster, which is built using Raspberry <i><b>Pi</b></i>'s and k<i><b>3s</b></i>. I try to adhere to GitOps methodologies using tools such as [Flux](https://fluxcd.io/), [Git(ea)](https://about.gitea.com/) and [K3s](https://k3s.io/).

## Hardware

| Device | OS Disk Size | Data Disk Size | Ram | OS | Function |
|:-------|:-------------|:---------------|:---:|:--:|:--------:|
| Raspberry Pi 4 | 128GB | 500GB (SSD) (Longhorn) | 8GB | DietPi | k3s control-plane |
| Raspberry Pi 4 | 128GB | / | 8GB | DietPi | k3s worker |
| Mikrotik hEX PoE | / | / | / | RouterOS | Switch (temp.) |