1. ncp server 샐성 + is_portal(          )
-  os에 disk 마운트 시에는 인스턴스 정지 시에만, 디스크 detach가 가능함. os에 디스크가 마운트 되어 있지 않다면, disk 추가 제거 가능 (자동으로 인스턴스 중지 하고 detach하는 옵션이 있음.*stop_instance_before_detaching)
-  인스턴스 실행 중에도, 디스크 연결은 가능함.
-  stop_instance_before_detaching = "true" : true일 경우 인스턴스가 자동 중지 되면서 디스크가 삭제는 되지만, 인스턴스가 다시 자동으로 살지 않음.
-  서버 스펙, 디스크 사이즈 변경은 os disk 마운트 유무 상관 없이, 서버 정지가 필요함 디스크 타입(ssd, hdd)등 사이즈 변경 이외에 모든 설정은 변경 불가능
