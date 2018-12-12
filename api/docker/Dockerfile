FROM node:8.14

EXPOSE 3001

# Create data directory
WORKDIR /app

# Copy application folder and configurations
COPY . /app

# INSTALL FOREVER
RUN npm install -g forever

CMD ["npm", "start"]