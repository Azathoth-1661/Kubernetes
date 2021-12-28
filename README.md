# Kubernetes 基礎介紹  
Kubernetes 是一個可移植的、可擴展的開源平台，用於管理容器化的工作負載和服務，可促進聲明式配置和自動化  
# 傳統部署時代 VS 虛擬化部署時代 VS 容器部署時代
![Image text](https://github.com/Azathoth-1661/Kubernetes/blob/main/container_evolution.svg)
### 傳統部屬時代

各個組織機構在物理服務器上運行應用程序。   

無法為物理服務器中的應用程序定義資源邊界，這會導致資源分配問題。   

例如，如果在物理服務器上運行多個應用程序，則可能會出現一個應用程序占用大部分資源的情況， 結果可能導致其他應用程序的性能下降。  

一種解決方案是在不同的物理服務器上運行每個應用程序，但是由於資源利用不足而無法擴展， 並且維護許多物理服務器的成本很高。

### 虛擬化部屬時代

虛擬化技術允許你在單個物理服務器的 CPU 上運行多個虛擬機（VM）。  

虛擬化允許應用程序在 VM 之間隔離，並提供一定程度的安全，因為一個應用程序的信息 不能被另一應用程序隨意訪問。

虛擬化技術能夠更好地利用物理服務器上的資源，並且因為可輕松地添加或更新應用程序 而可以實現更好的可伸縮性，降低硬件成本等等。

每個 VM 是一台完整的計算機，在虛擬化硬件之上運行所有組件，包括其自己的操作系統。

### 容器部屬時代
