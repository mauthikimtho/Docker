# Sử dụng image Node.js chính thức
FROM node:16

# Set thư mục làm việc trong container
WORKDIR /app

# Copy package.json và package-lock.json vào container
COPY package*.json ./

# Cài đặt các dependencies
RUN npm install

# Copy toàn bộ mã nguồn vào container
COPY . .

# Mở cổng 3000
EXPOSE 3000

# Lệnh để chạy ứng dụng
CMD ["node", "server.js"]
