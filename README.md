# Automatically_installing_Kubernetes
쿠버네티스 자동 쉘 스크립트 v1.29
- 가끔 Kubernetes 실습하다가 하기 싫을 때가 있습니다. 매번 밀어버리고 다시 설치하는 것도 일이라고 생각해서 만들었습니다.
- Version: 1.29v
- Cluster: Kubeadm

## 사용방법
- git clone 명령어를 이용하여 로컬로 파일 가져오기.
```sh
git clone https://github.com/WoogiBoogi1129/Automatically_installing_Kubernetes.git
```

- sh파일 권한 부여
```sh
chmod +x Automatically_installing_Kubernetes/k8s_auto_install.sh
```

- sh 파일 실행
```sh
sudo ./Automatically_installing_Kubernetes/k8s_auto_install.sh
```
