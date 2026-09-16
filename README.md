# Cycle Observer v2

PWA independente e offline para registro pessoal de biomarcadores do ciclo.

## Publicar gratuitamente no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie index.html, styles.css, app.js, manifest.json, sw.js e icon.svg para a raiz.
3. Settings > Pages > Build and deployment > Deploy from a branch.
4. Escolha main e /(root), depois Save.
5. Abra a URL HTTPS fornecida pelo GitHub.
6. No iPhone: Safari > Compartilhar > Adicionar à Tela de Início.

## Recursos v2
- Dashboard do ciclo
- Registro diário
- gráfico de 35 dias
- histórico e busca
- Peak manual
- relações, notas, medicamentos/sintomas
- importador conservador de Maya CSV
- exportação CSV e backup/restauração JSON
- funcionamento offline por service worker
- PIN local
- migração automática dos registros da v1

## Privacidade
Os dados são salvos em localStorage no navegador. O PIN bloqueia a interface, mas localStorage não deve ser tratado como armazenamento criptográfico de alta segurança. Proteja o aparelho e mantenha backups.

## Aviso
Projeto independente, não afiliado ao Creighton Model, FertilityCare ou NaProTECHNOLOGY. Não fornece diagnóstico nem determina fertilidade.
