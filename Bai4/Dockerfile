# Sử dụng Node.js image
FROM node:18

# Đặt thư mục làm việc trong container
WORKDIR /app

# Copy package.json và package-lock.json
COPY package*.json ./

# Cài đặt dependencies
RUN npm install

# Copy toàn bộ project vào container
COPY . .

# Expose port
EXPOSE 3000

# Lệnh chạy ứng dụng
CMD ["node", "server.js"]
