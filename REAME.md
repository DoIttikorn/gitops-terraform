# Architecture

## vpc

ใช้ในการสร้าง network ภายใน env แบ่งเป็น public subnet, private subnet

## route

ใช้ในการกำหนดว่าเส้นไหนต้องวิ่งไปไหน NAT GateWay

## igw internet gate way

เป็นตัวเชื่อม public internet

## nat-gateway

เป็นตัวเชื่อมตัว nat กับ public internet

## eks

kuberates กำหนด rule policy เชื่อมต่อ submit อะไรบ้าง depend on อะไรบ้าง

## eks-node

เป็นการกำหนด role node สร้าง node group และเป็นการสร้าง ec2
