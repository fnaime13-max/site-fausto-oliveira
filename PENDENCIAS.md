# Pendências — Site Nathan Lorena

Legenda: **[OBRIGATÓRIO]** resolver antes de publicar · **[CONFIRMAR]** está no site, mas foi escrito sem dado do cliente · **[DECISÃO]** precisa de aprovação.

## Dados profissionais
- **[OBRIGATÓRIO] CRN.** O rodapé mostra `CRN {{PREENCHER}}`. Toda publicidade de nutricionista precisa trazer nome e número do CRN.
- **[OBRIGATÓRIO] Formação (acima da cabeça, no hero).** Hoje mostra "Bacharel em Nutrição / CRN {{PREENCHER}}". Coloque faculdade e pós, se houver, no `<p class="study">` do `index.html`.
- **[OBRIGATÓRIO] Número de pacientes.** A seção Resultados mostra `+X`. Troque `data-count="X"` pelo número real (ex.: `data-count="350"`) e o texto `+X` dentro da mesma tag. O número conta sozinho ao aparecer. Use um número que ele consiga comprovar.
- **[CONFIRMAR] Cidade e formato.** O site não diz se o atendimento é presencial, on-line ou os dois, nem onde.

## Contato
- **[OBRIGATÓRIO] WhatsApp.** No `index.html`, preencha `const WHATSAPP = ""` só com dígitos (ex.: `5531999999999`). Enquanto estiver vazio, **nenhum dos botões de WhatsApp funciona**: todos só rolam até a seção de contato. Cada botão já tem a mensagem pronta (consulta, análise, dúvida e uma por especialidade).
- **[OBRIGATÓRIO] Instagram.** O link do rodapé aponta para `https://www.instagram.com/` genérico.

## Textos escritos sem dado do cliente
- **[CONFIRMAR] Especialidades:** Canetas emagrecedoras (Mounjaro/Ozempic), Dieta estratégica, Nutrição para treino, Emagrecimento, Saúde & exames, Reeducação alimentar. Cada cartão tem botão com mensagem pronta no WhatsApp.
- **[CONFIRMAR] Canetas:** o cartão diz que a prescrição é do médico. O nutricionista não prescreve o medicamento, por isso mantenha esse aviso.
- **[CONFIRMAR] "Marcar uma análise":** o que é a análise para ele (conversa inicial? é gratuita?). O site não diz que é gratuita.
- **[CONFIRMAR] Compromissos:** "1:1", "100%" e "0" descrevem o método e não prometem resultado.
- **[CONFIRMAR] Respostas da seção Dúvidas** e o texto "Eu mesmo respondo" do contato.

## Decisões tomadas
- **Sem depoimentos inventados.** O modelo original tinha depoimentos. Inventá-los seria falso e esbarra nas regras do CFN, por isso a seção virou "Dúvidas", com a mesma interação. O número de pacientes fica como `+X` até ele informar o valor real.
- **Fotos de fruta removidas** a pedido. O efeito de distorção no rosto também saiu.
- **Recorte da foto** feito por script (`_originais/cutout-dark.cjs`) a partir de `_originais/nathan-original.png`. O logo dourado da foto foi removido do retrato e extraído em `assets/logo-nl.png` / `logo-monograma.png`.
