# chat-system

## How to generate ID in multi DB

Single DB 構成の場合, ID の発行は auto_increment を使えば作られた順に ID がソートされて効率がいい

Multi Master DB 構成の場合、
snowflake の ID の発行を参考にすると ID が 64 ビットに収まり効率がいい

## Why Cassandra DB is recommended?
