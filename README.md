# Simon para Windows

Notas e projetos, com simplicidade.

**[Descarregar o Simon 0.2.7](https://github.com/XINOPITO/simon-releases/releases/download/v0.2.7/Instalar-Simon-0.2.7-candidato23.exe)** · [Ver todas as versões](https://github.com/XINOPITO/simon-releases/releases)

O instalador permite escolher as pastas do programa e dos dados. Versão preliminar para Windows de 64 bits.

## Atualizações

A partir da versão 0.2.7, o Simon procura e descarrega atualizações em segundo plano. A instalação acontece na abertura seguinte. Podes desligar esta opção no menu **Actualizações**.

Quem já usa uma versão anterior precisa de uma primeira atualização manual para receber este mecanismo. Conserva o perfil e o Vault existentes.

Os pacotes são verificados por assinatura Ed25519 e pelos hashes dos ficheiros. Esta assinatura de atualização é independente da assinatura de executáveis do Windows.

## O que está neste repositório

- `Instalar-Simon-*.exe`: instalador.
- `actualizacao.json`: manifesto assinado, usado pelo Simon.
- `pacote.simon.gz`: pacote descarregado pelo atualizador.

Não é necessário abrir o manifesto ou o pacote manualmente. Este repositório não contém notas pessoais, perfis, o Vault ou chaves privadas.
