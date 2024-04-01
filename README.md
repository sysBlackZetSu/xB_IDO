
Hiểu về Tiêu chuẩn ERC-20 (Ethereum Request For Comment) => Một tiêu chuẩn giao thức cho các token tiêu chuẩn dựa trên blockchain Ethereum. 
 - https://ethereum.org/en/developers/docs/standards/tokens/erc-20/
Hiểu sơ khái niệm Ngôn ngữ solidity 
 - https://docs.soliditylang.org/en/v0.8.25/
Nắm bắt các IDE (hardhat, truffle, ...)
 - https://hardhat.org/

Hiểu về mô hình Launchpad hoặc IDO (Initial DEX Offering) => đọc thêm: https://blog.accubits.com/what-is-initial-dex-offering-ido-and-its-benefits/

Hiểu về Địa chỉ của Smart Contract

Hiểu về Ethereum Virtual Machine (EVM)

Hiểu về ABI (Application Binary Interface) => giao diện mô tả các hàm và sự kiện có thể gọi được từ một smart contract

Ưu điểm, đặc điểm cơ bản của blockchain => ưu điểm của việc gọi vốn khi thông qua mạng blockchain.
 + Phân tán: Dữ liệu được lưu trữ trên nhiều nút (nodes) khác nhau trên mạng, thay vì tập trung vào một máy chủ duy nhất
 + Bảo mật: Dữ liệu trong mỗi khối được mã hóa bằng các thuật toán => đảm bảo tính bảo mật và toàn vẹn của thông tin.
 + Liên kết chuỗi: Mỗi khối chứa một mã hash của khối trước đó, tạo ra một liên kết chặt chẽ giữa các khối trong chuỗi.
 + Tính minh bạch: Mọi giao dịch được ghi lại trên blockchain là công khai và có thể kiểm tra được.
 + Không cần bên trung gian:  Blockchain loại bỏ sự phụ thuộc vào bên trung gian trong các giao dịch, giúp giảm thiểu chi phí và thời gian xử lý.

Hiểu về cơ chế gọi vốn (thông qua IDO hoặc Launchpad):
 - Như người dùng sẽ mua tokenA từ sàn DEX hoăc CEX? Ngoài ra, giá tokenA có bị thay đổi không (cố định hay thay đổi)?
 - Cơ chế Khóa (Vesting) thì có dựa hợp đồng gọi vốn để khóa tokenA ...

Hiểu về tokenomics => như cung cấp và phân phối token, cơ chế đốt token (nếu có), và các cơ chế khác để tạo ra giá trị và động lực cho người sở hữu token.

Hiểu về AMM (Automated Market Maker)

Hiểu về cơ chế giao tiếp giữa smart-contract và DApps (Interaction)
 - Transactions => các hành động thay đổi trạng thái của blockchain
 - Events  => cách mà smart contract thông báo về các hành động quan trọng đã xảy ra
 - Function Calls => gọi hàm của smart contract

Hiểu về Wallet Integration => Để sử dụng token ERC-20 trong các DApps
 - Connect, chủ yếu là Connecting to Ethereum: MetaMask
 - Signing Messages
   + Signer
   + Wallet
   + VoidSigner
   + ExternallyOwnedAccount
 - Thực Hiện Giao Dịch thông qua wallet
 - hiểu về JSON-RPC
   + JsonRpcSigner
   + JsonRpcUncheckedSigner
   + StaticJsonRpcProvider
   + Node-Specific Methods
 - các lib như web3.js, ethers.js
 - Import and export JSON wallets
 - Import and export BIP 39 mnemonic phrases (12 word backup phrases)
 - Gas Price, Gas Limit
 - Security
 - Các Provider API Keys: Etherscan, INFURA
