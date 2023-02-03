# prevendo_cancelamentos_de_reserva

Uma grande taxa de cancelamentos de reservas pode ser um problema para os hotéis. Pensando nisso, utilizei um dataset com dados sobre hospedagens de 2014 a 2017 para realizar uma análise exploratória e para criar um modelo que consiga prever com eficiência se um hóspede irá ou não cancelar sua reserva. 

Os resultados mostram que o modelo de Support Vector Machine (SVM) com validação cruzada, dados balanceados e ajuste de hiperparâmetros que utilziamos é eficaz em prever se um hóspede vai cancelar a sua reserva no hotel. Com uma taxa de recall de 0.91, o modelo acertou em prever 91% das vezes que o hóspede realmente cancelou a reserva.

Esses resultados são úteis para um hotel pois eles podem ajudar a gerenciar as reservas de forma mais eficiente. Por exemplo, o hotel pode tomar medidas preventivas para evitar cancelamentos de reservas previstos pelo modelo, ou pode ajustar sua estratégia de marketing para incentivar hóspedes a não cancelarem suas reservas.

Status do projeto: Concluido.

Artigo no Medium detalhando o projeto: https://medium.com/@edersonoliveira/previsão-de-cancelamento-de-reservas-2d1746d033ec

Dataset: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
