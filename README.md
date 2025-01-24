# musicbox

How to run the project:

1. Clone the repository
```bash
git clone https://github.com/kzha05/musicbox.git
```

2. Copy the .env.example file to .env
```bash
cp .env.example .env
```

OR

```bash
mv .env.example .env
```

3. Build the project
```bash
cd musicbox
docker-compose build
```

4. Run the project
```bash
docker-compose up -d
```

5. Run the migrations
```bash
docker-compose exec server php artisan migrate
```

Happy coding!