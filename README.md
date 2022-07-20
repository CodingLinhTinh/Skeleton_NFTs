# Skeleton_NFTs

![GitHub repo size](https://img.shields.io/github/repo-size/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/codinglinhtinh/Skeleton_NFTs?style=for-the-badge)

## Description
>Một NFT Engine có thể tạo 10 000 NFTs, sử dụng Pinata để upload các hình ảnh lên IPFS, sau đó sử dụng SmartContract upload các NFT đó lên OpenSea.

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

* Update các thông tin đã chỉnh sửa
```
node utils/update_info.js
```

==> Tất cả hình ảnh tạo được nằm ở <b>build</b>.

* Để upload lên OpenSea, cần có 1 ví như MetaMask. Sau khi có ví Metamask nên chuyển qua <b>Rineby Test Network</b>. Sau đó, t cần RinkebyETH, đi theo link này để nhận một ít ETH:

    ⭐<a href='https://faucet.rinkeby.io/'>RinkebyETH Faucet</a>

* Truy cập <a href='https://remix.ethereum.org/'>Remix IDE</a>, trong thư mục <b>contracts</b> tạo một file tên <b>MySmartContract.sol</b> như folder contract ở máy chúng ta.

* Vào <b>Deploy & Run Transaction</b>, đổi <b> Environment </b> thành: Wallect Connect. Nó yêu cầu ta INFURA Settings, truy cập <a href='https://infura.io/'>INFURA</a>, tạo một project và copy API KEY của nó dán vào INFURA Settings.

* Sau khi xong kết nối, ta đổi CONTRACT(Remix IDE) thành tên file của chúng ta, chọn <b>Deloy</b>.

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
