# ansible-netbox-vra
playbook tạo vm trên netbox thông qua vra

## Bước 1

- Tạo blueprint trên VRA, file mẫu `blueprint.yaml`

## Bước 2: Tạo playbook hello.yaml

Tạo playbook hello.yaml với nội dung giống file `hello.yaml` trên AWX

## Bước 3: Tạo playbook để add thông tin VM, IP lên netbox

Tạo file để lấy thông tin của VM từ VRA vào netbox. Nội dung giống file playbook-add-vm.yaml trên AWX
