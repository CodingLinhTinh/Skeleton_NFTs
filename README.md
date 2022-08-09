# Skeleton_NFTs

![GitHub repo size](https://img.shields.io/github/repo-size/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)

## Description
>Tạo được một NFT Engine có thể tạo nhiều NFT cùng lúc bằng cách ghép ngẫu nhiên các layer hình ảnh với nhau, sử dụng Pinata để upload các hình ảnh lên IPFS, bày các NFT đó trên OpenSea, sau đó sử dụng SmartContract mint các NFT đó.

## Getting Started
### 💻 Dependencies

* Cài đặt Node

    ⭐<a href='https://nodejs.org/en/download/'>NODE.JS</a>

* Tạo tài khoản Pinata

    ⭐<a href='https://app.pinata.cloud/'>PINATA</a>

    
### ⚙️ Uses

* Sau khi clone project này chạy lệnh này để cài đặt các package:
```
npm install
```

* Chỉnh sửa file <b>config.js</b>
Có thể chỉnh sửa ở /*START HERE*/ đến /*END HERE*/

* Sau khi chỉnh sửa xong chạy file <b>index.js</b>
```
node index.js
```
==> Tất cả hình ảnh tạo được nằm ở <b>build</b>.

* Truy cập Pinata, upload folder <b>images</b>, sau khi upload, copy CID vào src/config.js đổi YOUR_IMAGE_CID_PINATA thành mã CID, sau đó update các thông tin đã chỉnh sửa.

* Update các thông tin đã chỉnh sửa
```
node utils/update_info.js
```

* Sau đó upload folder json lên Pinata, copy các CID vào đâu đó để sử dụng ở Remix bên dưới.

* Để upload lên OpenSea, cần có 1 ví như MetaMask. Sau khi có ví Metamask nên chuyển qua <b>Rineby Test Network</b>. Sau đó, t cần RinkebyETH, đi theo link này để nhận một ít ETH:

    ⭐<a href='https://faucet.rinkeby.io/'>RinkebyETH Faucet</a>

* Truy cập <a href='https://remix.ethereum.org/'>Remix IDE</a>, trong thư mục <b>contracts</b> tạo một file tên <b>MySmartContract.sol</b>.

* Vào <b>Deploy & Run Transaction</b>, đổi <b> Environment </b> thành: Wallect Connect. Nó yêu cầu ta INFURA Settings, truy cập <a href='https://infura.io/'>INFURA</a>, tạo một project và copy API KEY của nó dán vào INFURA Settings.

* Sau khi xong kết nối, ta thêm file trong CONTRACT(Remix IDE), contract/MySmartContract.sol, chọn kênh để Deploy.

* Trước khi Deploy, điền tên các NFT, Symbol là tên các NFT, _INTBASEURI là 'ipfs://JSON_CID' (dán CID của Json vào)
![1](https://user-images.githubusercontent.com/92833984/183670916-c3033c05-a94f-4a43-9788-8730e46524ee.png)

===> Mở Opensea xem các file đã được upload chưa :<

### Preview
![45](https://user-images.githubusercontent.com/92833984/179915960-c561b539-95d0-4624-89b2-102d6eed4009.png)

<em>Một bé Skeleton số 11</em>

👉Có thể truy cập OpenSea của tôi để xem các NFTs: https://testnets.opensea.io/Ngoc-Quach

## 📫 Contributing to Skeleton_NFTs
Để đóng góp FISI hãy làm theo các bước sau:

    >1. Fork kho lưu trữ này.
    >2. Tạo một nhánh: `git checkout -b <branch_name>`.
    >3. Thực hiện các thay đổi của bạn và commit chúng: `` git commit -m '<commit_message>' '
    >4. Gửi đến nhánh gốc: `git push origin <project_name> / <location>`
    >5. Tạo yêu cầu fork.

Hoặc là thả sao ⭐⭐⭐⭐⭐

## 🔎 Help

Nếu có vấn đề gì hãy gửi lên ISSUES.
Thanks.

## 🧐 Authors

CodingLinhTinh 
[Gmail](ngocquachgamedevz@gmail.com)


## License

This project is licensed under the MIT License.

## See my other Blockchain repos

Update Later...
