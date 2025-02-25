<h1 align="center" style="font-weight: bold;">Food Ordering API</h1>

<p align="center">
   A Spring Boot-based food ordering API that enables users to browse a diverse selection of restaurants, place orders, and make payments seamlessly. The application integrates with the VNPay payment gateway and supports user registration for restaurant tenancy. 
</p>

## Technologies
- Backend: Spring Boot
- Frontend: ReactJS
- Storage: MySQL, Redis
- Others: Docker, Elastic Search, Debezium

## Details
- Employed JWT authentication and utilized Redis for token storage
- Integrated 3rd party services to handle payment and notification
- Leveraged ElasticSearch for lightning-fast search capabilities, powered by Kafka and Debezium for real-time data synchronization
- VNPay integration for secured payment
- Shopping cart & order management
- Allowed users to leave comments on products and restaurants.
- Registration for restaurant tenenacy is available
- Restaurant owners can efficiently manage their menus, operating hours, and food offerings.

## Execution
Docker installation is required on your machine.

Reference
- **[Docker installation](https://docs.docker.com/engine/install/)**

Run Elastic Search

```sh
cd ./elastic-search
docker compose up
cd ../..
```

Run Redis

```sh
docker compose up
```

## Additional Information
Mock VNPay Payment Information
```
Ngân hàng: NCB
Số thẻ: 9704198526191432198
Tên chủ thẻ: NGUYEN VAN A
Ngày phát hành: 07/15
Mật khẩu OTP: 123456
```

## Contribution
We appreciate all your contributions! Feel free to open issues, submit pull requests, or share your feedback to help improve the project.

