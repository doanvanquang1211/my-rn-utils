* Tạo module mới bằng TypeScript
mkdir my-react-native-module
cd my-react-native-module
npm init -y
npm install react-native typescript @types/react --save-peer
npx tsc --init


* Cấu trúc
my-react-native-module/
├── src/
│   └── index.ts
├── package.json
├── tsconfig.json

* Lệnh build
npm run build