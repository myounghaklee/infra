# infra

# Docker Container
������ �����̳� ���� ���� �������̴�. 
�������� ���μ���, ����, ��Ʈ��ũ, �������̽�, ����Ʈ ���� ������ �ִ�. 
������ os���� os kernel�� software �� �����Ǿ��ִ�. 
os kernel�� ��� �ϵ����� ��ȣ �ۿ��ϴ� ������ �ϸ� ����Ʈ����� ui, ����̹� ���� ������, ������ �� ���� �ִ�. 

Docker�� ���� Ŀ���� ������ �ִٸ� � �ü���� ���� �� �� �ִ�. 
 

 ## docker ��ɾ� ����
 `docker run -p 8080:80 [imageId]` : -p�� publish �ɼ� �̹Ƿ� 8080��Ʈ�� ���� ������ dockerfile�� `EXPOSE 80 `�� ����س��Ҵٸ� 80 ��Ʈ�� ���� �ض�

 ### Image ���� ��ɾ�

- `-t` : �±� 
- docker images : �̹��� list show
- docker image inspect : �̹��� �м�
- docker rmi, docker prune : �̹��� ���� 

### Container ���� ��ɾ�
- `--name`: �����̳� ���� ����
- see --help : ���λ��� ���� 
- docker ps : �����̳� ����Ʈ
- docker rm : �����̳� ����