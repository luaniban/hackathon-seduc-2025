# Hackathon SEDUC 2025 — Águia do Asfalto

Projeto da equipe Águia do Asfalto no 1º Hackathon da Secretaria de Educação de Caraguatatuba (novembro de 2025). A equipe ficou em 3º lugar com o app De Casa para Escola.

## O que tem

- Cadastro do estudante para o transporte universitário, em etapas: dados pessoais, dados acadêmicos, informações de bolsa e termo de confirmação.
- CRUD de estudantes.
- CRUD de usuários, com cargos.
- Dashboard e layout com a logo da equipe.

## Tecnologias

- Laravel 12, Jetstream, Livewire 3 e Volt
- TallStackUI e Tailwind CSS 4
- SQLite

## Como rodar

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed   # usa SQLite (database/database.sqlite)
npm install
npm run dev
php artisan serve
```
