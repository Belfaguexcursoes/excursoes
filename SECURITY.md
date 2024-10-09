# Criando o conteúdo da política de segurança em formato Markdown
politica_seguranca_md = """
# Política de Segurança

## Versões Suportadas
A segurança do nosso site é uma prioridade. As seguintes versões do nosso projeto estão atualmente sendo suportadas com atualizações de segurança:

| Versão   | Suportado |
|----------|-----------|
| 5.1.x    | ✅        |
| 5.0.x    | ❌        |
| 4.0.x    | ✅        |
| < 4.0    | ❌        |

As versões não suportadas não recebem atualizações de segurança e, portanto, não são recomendadas para uso.

## Relatando uma Vulnerabilidade
Se você identificar uma vulnerabilidade em nosso site, agradecemos sua ajuda para relatar isso. Para relatar uma vulnerabilidade, siga as diretrizes abaixo:

1. **Como Relatar**: 
   - Envie um e-mail para felipebertolin22@gmail.com com uma descrição detalhada da vulnerabilidade. Inclua informações sobre como reproduzir o problema, se possível.

2. **Respostas e Atualizações**:
   - Assim que recebermos sua notificação, confirmaremos o recebimento em até 3 dias úteis.
   - Manteremos você informado sobre o progresso da análise da vulnerabilidade relatada, incluindo um cronograma aproximado para a resolução. 

3. **O que Esperar**:
   - Se a vulnerabilidade for aceita, trabalharemos rapidamente para desenvolver e implementar uma correção. Você será notificado quando a correção for implementada e quando uma atualização de segurança for liberada.
   - Se a vulnerabilidade for considerada não crítica ou se não puder ser reproduzida, entraremos em contato para informá-lo sobre a decisão e forneceremos uma explicação.

4. **Confidencialidade**:
   - Todos os relatórios de vulnerabilidades serão tratados com a máxima confidencialidade e não serão divulgados publicamente sem a sua autorização.

5. **Agradecimento**:
   - Valorizamos a contribuição da comunidade para a segurança do nosso site e agradecemos qualquer relatório de vulnerabilidade. Dependendo da gravidade da vulnerabilidade, podemos considerar o reconhecimento público ou uma recompensa simbólica como agradecimento.

## Compromisso com a Segurança
Nosso compromisso é manter um ambiente seguro para todos os usuários. Continuamos a revisar e atualizar nossas práticas de segurança para proteger as informações de nossos usuários e garantir a integridade de nosso site.
"""

# Salvando o conteúdo em um arquivo .md
caminho_arquivo = '/mnt/data/politica_de_seguranca.md'
with open(caminho_arquivo, 'w') as arquivo:
    arquivo.write(politica_seguranca_md)

