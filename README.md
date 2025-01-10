# Open Source Devops Learning App with 15 Projects to build in 2025
Open Source Devops Learning App with 15 Projects to build in 2025
Time and again the message everyone is trying to convey to budding devops engineers/learners is "Build Real World Skill", build projects, use an open source app etc. However the problems I realize with most such apps are,

They are mostly hello world types

Are outdated (code, tech stack)

Are not actively maintained

Lack unit test cases, integration tests

Are complex to build. Most people give up just installing it

Not documented

So in 2024 I built a micro services app with the purpose of helping devops folks build Real World Devops Skills. here is what I have incorporated into this app so far .

1. Modern Tech Stack: It uses the most in demand tech stack that you would find topping in Stackoverflow Survey e.g. NodeJS with Express.js, Python, Golang, Springboot , Mongo and Postgres.

2. Iterative Builds : You could built it iteratively : one of the reasons why people give up learning is if they find it too difficult and complex to build something. Most of the apps take you to have everything configured in order to show the nice working UI. Our app gives you small, quick wins where you can start with frontent immediately and then add more services

3. System Info:  It shows you all the useful info from frontend : you want to know whether your app is running as a container ? Is it running on a kuberneres cluster? whats the IP address  and hostname (useful when you are working with load balancers/services etc.

4. Test Cases: It has working unit and integration tests, which are not always avaiable in other hello world type apps that you build.

5. Service Dashboard: It gives you service monitoring dashboard which tells you whether you have backend services available or not

6. UI for API Services: It also shows you a simple yet nice UI to validate you have each backend service working 7. It allows you to deploy the app without setting up mongo and postgres using sqlite and json files, at the same time allow you to migrate to those databased when you are ready.

7. App Version : When you are deploying new versions, its easy to just bump up the version, build a new image and push. Viola, you get a immediate visual feedback when the new version is up.

7. Well Documented:  I have tried to add as much description on the architecture, tech stack, the reasoning behind using a particular tech, key features etc.

Its available as open source for everyone to play with https://github.com/craftista/craftista

Do give it a spin and let me know what else would you like to see in this app. How could we make it even better ?

If you are looking for project ideas to learn using this app

Here are 10 basic projects you could build with it that would make you a Real Devops Engineer

Containerize with Docker: Write Dockerfiles for each of the services, and a docker compose to run it as a micro services application stack to automate dev environments.

Build CI Pipeline : Build a complete CI Pipeline using Jenkins, GitHub Actions, Azure Devops etc.

Deploy to Kubernetes : Write kubernetes manifests to create Deployments, Services, PVCs, ConfigMaps, Statefulsets and more

Package with Helm : Write helm charts to templatize the kubernetes manifests and prepare to deploy in different environments

Blue/Green and Canary Releases with ArgoCD/GitOps: Setup releases strategies with Argo Rollouts Combined with ArgoCD and integrate with CI Pipeline created in 3. to setup a complete CI/CD workflow.

Setup Observability : Setup monitoring with Prometheus and Grafana (Integrate this for automated CD with rollbacks using Argo), Setup log management with ELS/EFK Stack or Splunk.

Build a DevSecOps Pipeline: Create a DevSecOps Pipeline by adding SCA, SAST, Image Scanning, DAST, Compliance Scans, Kubernetes Scans etc. and more at each stage.

Design and Build Cloud Infra : Build Scalable, Hight Available, Resilience, Fault Tolerance Cloud Infra to host this app.

Write Terraform Templating : Automate the infra designed in project 8. Use Terragrunt on top for multi environment configurations.

Python Scripts for Automation : Automate ad-hoc tasks using python scripts.

and if you want to take it to the next level here are 5 Advanced Projects:

Deploy on EKS/AKS: Build EKS/AKS Cluster and deploy this app with helm packages you created earlier.

Implement Service Mesh: Setup advanced observability, traffic management and shaping, mutual TLS, client retries and more with Istio.

AIOps: On top of Observability, incorporate Machine Learning models, Falco and Argo Workflow for automated monitoring, incident response and mitigation.

SRE: Implement SLIs, SLOs, SLAs on top of the project 6 and setup Site Reliability Engineering practices.

Chaos Engineering : Use LitmusChaos to test resilience of your infra built on Cloud with Kubernetes and Istio.

If you just want to take a look at the app by launching it in 5 minutes (if you have docker installed already), head over to https://github.com/craftista/craftista-demo and follow the instructions there.

If you are interested in contributing to this project, just fork it, add your love and send me a PR. Do PM me in case if you want to actively maintain and contribute to it.

And if you like this project and think it deserves one, feel free to add a GitHub star :)

===========================================================================

Open Source DevOps Learning App với 15 Dự Án để xây dựng vào năm 2025
Giới thiệu
Thường xuyên, thông điệp mà mọi người muốn truyền tải đến các kỹ sư DevOps mới là "Xây dựng kỹ năng thực tế", xây dựng dự án, sử dụng ứng dụng mã nguồn mở, v.v. Tuy nhiên, các vấn đề thường gặp với hầu hết các ứng dụng này là:

Chủ yếu là các ứng dụng "Hello World" đơn giản.
Công nghệ lạc hậu hoặc không được duy trì.
Thiếu các trường hợp kiểm thử đơn vị và tích hợp.
Quá phức tạp để xây dựng; nhiều người từ bỏ ngay từ bước cài đặt.
Thiếu tài liệu hướng dẫn chi tiết.
Vì vậy, vào năm 2024, tôi đã xây dựng một ứng dụng microservices với mục đích giúp các bạn học DevOps xây dựng Kỹ năng DevOps Thực tế.

Link GitHub: https://github.com/craftista/craftista

Tính năng của ứng dụng
Công nghệ hiện đại:

Sử dụng các công nghệ phổ biến và được ưa chuộng như NodeJS với Express.js, Python, Golang, Spring Boot, MongoDB và PostgreSQL.
Xây dựng theo từng bước:

Cho phép bạn xây dựng ứng dụng theo từng bước nhỏ, bắt đầu với frontend và dần dần thêm các dịch vụ backend.
Thông tin hệ thống:

Hiển thị thông tin hữu ích từ frontend như ứng dụng có đang chạy trong container hay không, chạy trên Kubernetes, địa chỉ IP, hostname, v.v.
Kiểm thử:

Bao gồm các bài kiểm thử đơn vị và tích hợp hoạt động, giúp bạn hiểu rõ hơn về tầm quan trọng của kiểm thử trong phát triển phần mềm.
Bảng điều khiển dịch vụ:

Cung cấp dashboard giám sát dịch vụ, cho biết trạng thái của các dịch vụ backend.
Giao diện người dùng cho API Services:

Giao diện đơn giản giúp bạn xác minh hoạt động của từng dịch vụ backend.
Triển khai linh hoạt:

Cho phép triển khai ứng dụng mà không cần cài đặt MongoDB và PostgreSQL bằng cách sử dụng SQLite và file JSON, và chuyển đổi sang cơ sở dữ liệu khác khi bạn sẵn sàng.
Quản lý phiên bản ứng dụng:

Dễ dàng tăng phiên bản, xây dựng image mới và đẩy lên, cung cấp phản hồi trực quan ngay lập tức khi phiên bản mới hoạt động.
Tài liệu chi tiết:

Cung cấp mô tả về kiến trúc, công nghệ, lý do lựa chọn công nghệ và các tính năng chính.
10 Dự Án Cơ Bản để Xây Dựng Kỹ Năng DevOps
Container hóa với Docker:

Viết Dockerfile cho mỗi dịch vụ.
Sử dụng Docker Compose để chạy toàn bộ ứng dụng microservices.
Tự động hóa môi trường phát triển.
Xây dựng Pipeline CI:

Thiết lập pipeline CI bằng Jenkins, GitHub Actions hoặc Azure DevOps.
Tích hợp kiểm thử và xây dựng tự động.
Triển khai lên Kubernetes:

Viết manifest Kubernetes để tạo Deployments, Services, PersistentVolumeClaims, ConfigMaps, StatefulSets, v.v.
Hiểu về orchestration và quản lý container.
Đóng gói với Helm:

Viết chart Helm để tạo mẫu cho manifest Kubernetes.
Chuẩn bị cho việc triển khai ở các môi trường khác nhau.
Triển khai Blue/Green và Canary với ArgoCD/GitOps:

Thiết lập chiến lược phát hành với Argo Rollouts kết hợp ArgoCD.
Tích hợp với pipeline CI để tạo luồng công việc CI/CD hoàn chỉnh.
Thiết lập Observability:

Cài đặt giám sát với Prometheus và Grafana.
Thiết lập log management với ELS/EFK Stack hoặc Splunk.
Tích hợp tự động rollback bằng Argo.
Xây dựng Pipeline DevSecOps:

Thêm SCA (Software Composition Analysis), SAST (Static Application Security Testing), quét image, DAST (Dynamic Application Security Testing), kiểm tra tuân thủ, quét Kubernetes, v.v. vào mỗi giai đoạn của pipeline.
Thiết kế và xây dựng hạ tầng Cloud:

Xây dựng hạ tầng đám mây mở rộng, sẵn sàng cao, có khả năng chịu lỗi để lưu trữ ứng dụng.
Áp dụng các nguyên tắc về khả năng mở rộng và độ tin cậy.
Viết Terraform Templating:

Tự động hóa hạ tầng đã thiết kế ở dự án 8 bằng Terraform.
Sử dụng Terragrunt cho cấu hình nhiều môi trường.
Script Python cho tự động hóa:

Tự động hóa các nhiệm vụ ad-hoc bằng script Python.
Tối ưu hóa quy trình và giảm thiểu công việc thủ công.
5 Dự Án Nâng Cao để Nâng Tầm Kỹ Năng
Triển khai trên EKS/AKS:

Xây dựng cluster EKS (Amazon Elastic Kubernetes Service) hoặc AKS (Azure Kubernetes Service).
Triển khai ứng dụng với các gói Helm đã tạo.
Triển khai Service Mesh với Istio:

Thiết lập observability nâng cao, quản lý và điều chỉnh lưu lượng.
Áp dụng mutual TLS, client retries và các tính năng khác của Istio.
AIOps:

Tích hợp mô hình Machine Learning.
Sử dụng Falco và Argo Workflow để giám sát tự động, phản ứng và khắc phục sự cố.
Thực hành SRE (Site Reliability Engineering):

Thực hiện các SLI (Service Level Indicators), SLO (Service Level Objectives), SLA (Service Level Agreements).
Thiết lập các thực hành SRE để cải thiện độ tin cậy hệ thống.
Chaos Engineering:

Sử dụng LitmusChaos để kiểm tra khả năng chịu lỗi của hạ tầng đám mây.
Xây dựng hệ thống có khả năng tự phục hồi và chống chịu sự cố.
Bắt đầu như thế nào?
Thử nghiệm ứng dụng:

Truy cập Craftista trên GitHub để khám phá mã nguồn và tài liệu.
Triển khai ứng dụng trong 5 phút nếu bạn đã cài đặt Docker bằng cách theo hướng dẫn tại craftista-demo.
Đóng góp cho dự án:

Fork repository, thêm đóng góp của bạn và gửi pull request.
Liên hệ nếu bạn muốn tích cực duy trì và đóng góp cho dự án.
Kết luận
Các dự án trên cung cấp cho bạn một lộ trình toàn diện để phát triển kỹ năng DevOps thực tế. Bằng cách thực hiện chúng, bạn sẽ có được kinh nghiệm thực tiễn với các công cụ và phương pháp hiện đại, chuẩn bị tốt cho sự nghiệp trong lĩnh vực DevOps.

Nếu bạn thấy dự án này hữu ích, hãy thêm một ngôi sao trên GitHub!

Chúc bạn thành công trên con đường học tập và phát triển sự nghiệp DevOps của mình!
