<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel Financeiro - Setor de Vendas</title>
    <style>
        /* Estilos Globais */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f0f4f8;
            color: #333;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.08);
        }

        h1, h2, h3 {
            text-align: center;
            color: #1e293b;
            margin-top: 0;
        }

        .subtitle {
            text-align: center;
            color: #64748b;
            margin-bottom: 25px;
        }

        .btn-back {
            background-color: #64748b;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            margin-bottom: 20px;
            transition: background 0.2s;
        }
        .btn-back:hover {
            background-color: #475569;
        }

        /* Painel de Metas */
        .goals-panel {
            background: #f8fafc;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 25px;
        }

        .goals-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin-top: 15px;
        }

        @media (max-width: 768px) {
            .goals-grid { grid-template-columns: 1fr; }
        }

        .goal-card {
            background: white;
            padding: 15px;
            border-radius: 8px;
            border: 1px solid #cbd5e1;
        }

        .goal-card label {
            font-size: 0.9em;
            color: #475569;
            font-weight: 600;
        }

        .goal-card input {
            width: 100%;
            padding: 8px;
            margin: 5px 0 10px 0;
            border: 1px solid #cbd5e1;
            border-radius: 4px;
            font-weight: bold;
            box-sizing: border-box;
            text-align: right;
        }

        .goal-card input:disabled {
            background-color: #f1f5f9;
            color: #64748b;
            border-color: #e2e8f0;
        }

        .progress-container {
            background-color: #e2e8f0;
            border-radius: 10px;
            overflow: hidden;
            height: 18px;
            position: relative;
            margin-top: 5px;
        }

        .progress-bar {
            height: 100%;
            width: 0%;
            transition: width 0.4s ease;
        }

        .progress-bar.consorcio-bar { background-color: #3b82f6; }
        .progress-bar.seguro-bar { background-color: #eab308; }
        .progress-bar.invest-bar { background-color: #10b981; }
        .progress-bar.credito-bar { background-color: #a855f7; }
        .progress-bar.contas-bar { background-color: #f97316; }
        .progress-bar.visitas-bar { background-color: #ec4899; }

        .progress-text {
            position: absolute;
            width: 100%;
            text-align: center;
            top: 1px;
            font-size: 0.8em;
            font-weight: bold;
            color: #0f172a;
        }

        /* Grid de Meses */
        .months-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }

        @media (max-width: 600px) {
            .months-grid { grid-template-columns: repeat(2, 1fr); }
        }

        .month-card {
            background: #ffffff;
            border: 2px solid #cbd5e1;
            border-radius: 10px;
            padding: 20px 15px;
            text-align: center;
            font-size: 1.2em;
            font-weight: bold;
            color: #334155;
            cursor: pointer;
            transition: all 0.2s ease;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            gap: 5px;
        }

        .month-card:hover {
            background-color: #0284c7;
            color: white;
            border-color: #0284c7;
            transform: translateY(-3px);
        }

        .month-percentage {
            font-size: 0.70em;
            color: #0284c7;
            font-weight: 600;
            background: #e0f2fe;
            padding: 2px 8px;
            border-radius: 12px;
            transition: all 0.2s;
        }

        .month-card:hover .month-percentage {
            background: #0369a1;
            color: white;
        }

        /* Grid de Dias */
        .days-grid {
            display: grid;
            grid-template-columns: repeat(7, 1fr);
            gap: 10px;
        }

        .day-cell {
            aspect-ratio: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background-color: #ffffff;
            border: 2px solid #e2e8f0;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            position: relative;
            transition: all 0.2s;
        }

        .day-cell:hover {
            background-color: #38bdf8;
            color: white;
            border-color: #38bdf8;
        }

        .day-cell.has-data {
            border-color: #10b981;
            background-color: #f0fdf4;
        }

        .badge-count {
            position: absolute;
            top: 4px;
            right: 4px;
            background: #10b981;
            color: white;
            font-size: 0.7em;
            padding: 2px 6px;
            border-radius: 10px;
        }

        /* Formulário e Tabelas */
        .form-section {
            background: #f8fafc;
            padding: 20px;
            border-radius: 8px;
            border: 1px solid #e2e8f0;
            margin-bottom: 30px;
        }

        form {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
        }

        @media (max-width: 600px) {
            form { grid-template-columns: 1fr; }
        }

        .form-group {
            display: flex;
            flex-direction: column;
            gap: 5px;
        }

        .form-group.full-width {
            grid-column: span 2;
        }

        @media (max-width: 600px) {
            .form-group.full-width { grid-column: span 1; }
        }

        label {
            font-weight: 600;
            color: #475569;
        }

        input {
            padding: 10px;
            border: 2px solid #cbd5e1;
            border-radius: 6px;
            font-size: 1em;
        }

        input.mask-moeda, input.mask-qtd {
            text-align: right;
            font-weight: bold;
        }

        input:focus {
            border-color: #0284c7;
            outline: none;
        }

        .btn-submit {
            grid-column: span 2;
            background-color: #10b981;
            color: white;
            padding: 12px;
            border: none;
            border-radius: 6px;
            font-size: 1em;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.2s;
        }

        @media (max-width: 600px) {
            .btn-submit { grid-column: span 1; }
        }

        .btn-submit:hover {
            background-color: #059669;
        }

        /* Tabela Histórica */
        .table-container {
            overflow-x: auto;
            margin-top: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
            font-size: 0.95em;
        }

        th, td {
            text-align: left;
            padding: 12px;
            border-bottom: 1px solid #e2e8f0;
            white-space: nowrap;
        }

        th {
            background-color: #f1f5f9;
            color: #475569;
            font-weight: 600;
        }

        tr:hover {
            background-color: #f8fafc;
        }

        .btn-action {
            padding: 5px 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-weight: bold;
            font-size: 0.85em;
            margin-right: 5px;
            transition: background 0.2s;
        }

        .btn-edit { background-color: #3b82f6; color: white; }
        .btn-edit:hover { background-color: #1d4ed8; }
        .btn-delete { background-color: #ef4444; color: white; }
        .btn-delete:hover { background-color: #b91c1c; }
    </style>
</head>
<body>

    <div class="container">
        
        <div id="monthView">
            <h1>Setor Financeiro</h1>
            <p class="subtitle">Defina as metas globais do ano e selecione o mês de competência</p>
            
            <div class="goals-panel">
                <h3>Planejamento de Metas Anuais</h3>
                <div class="goals-grid">
                    <div class="goal-card">
                        <label for="metaAnoConsorcio">Meta Ano Consórcio (R$):</label>
                        <input type="text" id="metaAnoConsorcio" class="mask-moeda" value="600.000,00">
                    </div>
                    <div class="goal-card">
                        <label for="metaAnoSeguro">Meta Ano Seguro (R$):</label>
                        <input type="text" id="metaAnoSeguro" class="mask-moeda" value="240.000,00">
                    </div>
                    <div class="goal-card">
                        <label for="metaAnoInvest">Meta Ano Investimentos (R$):</label>
                        <input type="text" id="metaAnoInvest" class="mask-moeda" value="360.000,00">
                    </div>
                    <div class="goal-card">
                        <label for="metaAnoCredito">Meta Ano Crédito Total (R$):</label>
                        <input type="text" id="metaAnoCredito" class="mask-moeda" value="1.200.000,00">
                    </div>
                    <div class="goal-card">
                        <label for="metaAnoContas">Meta Ano Contas Abertas (Qtd):</label>
                        <input type="text" id="metaAnoContas" class="mask-qtd" value="1.200">
                    </div>
                    <div class="goal-card">
                        <label for="metaAnoVisitas">Meta Ano Visitas Totais (Qtd):</label>
                        <input type="text" id="metaAnoVisitas" class="mask-qtd" value="2.400">
                    </div>
                </div>
            </div>

            <div class="months-grid" id="monthsGrid"></div>
        </div>

        <div id="dayView" style="display: none;">
            <button class="btn-back" id="backToMonthsBtn">← Voltar para Metas Anuais</button>
            <h2 id="dayViewTitle">Mês</h2>
            <p class="subtitle">Metas calculadas (1/12 do ano) e acompanhamento mensal</p>
            
            <div class="goals-panel">
                <h3>Metas Calculadas para este Mês</h3>
                <div class="goals-grid">
                    <div class="goal-card">
                        <label>Meta Consórcio do Mês:</label>
                        <input type="text" id="metaConsorcioInput" class="mask-moeda" disabled>
                        <div><small>Realizado: <span id="realizadoConsorcio">R$ 0,00</span></small></div>
                        <div class="progress-container">
                            <div class="progress-bar consorcio-bar" id="barConsorcio"></div>
                            <div class="progress-text" id="txtConsorcio">0%</div>
                        </div>
                    </div>
                    <div class="goal-card">
                        <label>Meta Seguro do Mês:</label>
                        <input type="text" id="metaSeguroInput" class="mask-moeda" disabled>
                        <div><small>Realizado: <span id="realizadoSeguro">R$ 0,00</span></small></div>
                        <div class="progress-container">
                            <div class="progress-bar seguro-bar" id="barSeguro"></div>
                            <div class="progress-text" id="txtSeguro">0%</div>
                        </div>
                    </div>
                    <div class="goal-card">
                        <label>Meta Investimentos do Mês:</label>
                        <input type="text" id="metaInvestInput" class="mask-moeda" disabled>
                        <div><small>Realizado: <span id="realizadoInvest">R$ 0,00</span></small></div>
                        <div class="progress-container">
                            <div class="progress-bar invest-bar" id="barInvest"></div>
                            <div class="progress-text" id="txtInvest">0%</div>
                        </div>
                    </div>
                    <div class="goal-card">
                        <label>Meta Crédito do Mês:</label>
                        <input type="text" id="metaCreditoInput" class="mask-moeda" disabled>
                        <div><small>Realizado: <span id="realizadoCredito">R$ 0,00</span></small></div>
                        <div class="progress-container">
                            <div class="progress-bar credito-bar" id="barCredito"></div>
                            <div class="progress-text" id="txtCredito">0%</div>
                        </div>
                    </div>
                    <div class="goal-card">
                        <label>Meta Contas do Mês:</label>
                        <input type="text" id="metaContasInput" class="mask-qtd" disabled>
                        <div><small>Realizado: <span id="realizadoContas">0</span></small></div>
                        <div class="progress-container">
                            <div class="progress-bar contas-bar" id="barContas"></div>
                            <div class="progress-text" id="txtContas">0%</div>
                        </div>
                    </div>
                    <div class="goal-card">
                        <label>Meta Visitas do Mês:</label>
                        <input type="text" id="metaVisitasInput" class="mask-qtd" disabled>
                        <div><small>Realizado: <span id="realizadoVisitas">0</span></small></div>
                        <div class="progress-container">
                            <div class="progress-bar visitas-bar" id="barVisitas"></div>
                            <div class="progress-text" id="txtVisitas">0%</div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="days-grid" id="daysGrid"></div>
        </div>

        <div id="formView" style="display: none;">
            <button class="btn-back" id="backToDaysBtn">← Voltar para os Dias</button>
            <h2 id="formTitle">Lançamentos do Dia</h2>
            <p class="subtitle">Insira múltiplos clientes e visualize o histórico do dia abaixo</p>
            
            <div class="form-section">
                <h3 id="formSectionTitle">Novo Lançamento</h3>
                <form id="financeForm">
                    <div class="form-group full-width">
                        <label for="cliente">Cliente (Nome Completo):</label>
                        <input type="text" id="cliente" placeholder="Nome do cliente" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="consorcio">Consórcio (R$):</label>
                        <input type="text" id="consorcio" class="mask-moeda" value="0,00">
                    </div>

                    <div class="form-group">
                        <label for="seguro">Seguro (R$):</label>
                        <input type="text" id="seguro" class="mask-moeda" value="0,00">
                    </div>

                    <div class="form-group">
                        <label for="investimentos">Investimentos (R$):</label>
                        <input type="text" id="investimentos" class="mask-moeda" value="0,00">
                    </div>

                    <div class="form-group">
                        <label for="credito">Crédito Total (R$):</label>
                        <input type="text" id="credito" class="mask-moeda" value="0,00">
                    </div>

                    <div class="form-group">
                        <label for="contas">Contas Abertas (Qtd):</label>
                        <input type="text" id="contas" class="mask-qtd" value="0">
                    </div>

                    <div class="form-group">
                        <label for="visitas">Visitas Totais (Qtd):</label>
                        <input type="text" id="visitas" class="mask-qtd" value="0">
                    </div>

                    <button type="submit" class="btn-submit" id="submitBtn">Adicionar Lançamento</button>
                </form>
            </div>

            <div class="form-section">
                <h3>Lançamentos Realizados neste Dia</h3>
                <div class="table-container">
                    <table>
                        <thead>
                            <tr>
                                <th>Cliente</th>
                                <th>Consórcio</th>
                                <th>Seguro</th>
                                <th>Investimentos</th>
                                <th>Crédito Total</th>
                                <th>Contas Abertas</th>
                                <th>Visitas Totais</th>
                                <th>Ações</th>
                            </tr>
                        </thead>
                        <tbody id="lancamentosTableBody">
                            </tbody>
                    </table>
                </div>
            </div>
        </div>

    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Elementos de Telas
            const monthView = document.getElementById('monthView');
            const dayView = document.getElementById('dayView');
            const formView = document.getElementById('formView');
            
            // Elementos de Conteúdo
            const monthsGrid = document.getElementById('monthsGrid');
            const daysGrid = document.getElementById('daysGrid');
            const dayViewTitle = document.getElementById('dayViewTitle');
            const formTitle = document.getElementById('formTitle');
            const formSectionTitle = document.getElementById('formSectionTitle');
            const financeForm = document.getElementById('financeForm');
            const submitBtn = document.getElementById('submitBtn');
            const lancamentosTableBody = document.getElementById('lancamentosTableBody');
            
            // Inputs de Metas Anuais
            const metaAnoConsorcio = document.getElementById('metaAnoConsorcio');
            const metaAnoSeguro = document.getElementById('metaAnoSeguro');
            const metaAnoInvest = document.getElementById('metaAnoInvest');
            const metaAnoCredito = document.getElementById('metaAnoCredito');
            const metaAnoContas = document.getElementById('metaAnoContas');
            const metaAnoVisitas = document.getElementById('metaAnoVisitas');

            // Inputs de Metas Mensais
            const metaConsorcioInput = document.getElementById('metaConsorcioInput');
            const metaSeguroInput = document.getElementById('metaSeguroInput');
            const metaInvestInput = document.getElementById('metaInvestInput');
            const metaCreditoInput = document.getElementById('metaCreditoInput');
            const metaContasInput = document.getElementById('metaContasInput');
            const metaVisitasInput = document.getElementById('metaVisitasInput');

            // Textos e Barras de Realizado
            const realizadoConsorcio = document.getElementById('realizadoConsorcio');
            const realizadoSeguro = document.getElementById('realizadoSeguro');
            const realizadoInvest = document.getElementById('realizadoInvest');
            const realizadoCredito = document.getElementById('realizadoCredito');
            const realizadoContas = document.getElementById('realizadoContas');
            const realizadoVisitas = document.getElementById('realizadoVisitas');
            
            const barConsorcio = document.getElementById('barConsorcio');
            const barSeguro = document.getElementById('barSeguro');
            const barInvest = document.getElementById('barInvest');
            const barCredito = document.getElementById('barCredito');
            const barContas = document.getElementById('barContas');
            const barVisitas = document.getElementById('barVisitas');

            const txtConsorcio = document.getElementById('txtConsorcio');
            const txtSeguro = document.getElementById('txtSeguro');
            const txtInvest = document.getElementById('txtInvest');
            const txtCredito = document.getElementById('txtCredito');
            const txtContas = document.getElementById('txtContas');
            const txtVisitas = document.getElementById('txtVisitas');

            // Botões de navegação
            const backToMonthsBtn = document.getElementById('backToMonthsBtn');
            const backToDaysBtn = document.getElementById('backToDaysBtn');

            // Estado Global
            let selectedMonth = null;
            let selectedDay = null;
            let editingIndex = null;

            // Banco de Dados Local
            const dbFinanceiro = {};
            const meses = [
                'Janeiro', 'Fevereiro', 'Março', 'Abril', 'Maio', 'Junho',
                'Julho', 'Agosto', 'Setembro', 'Outubro', 'Novembro', 'Dezembro'
            ];

            meses.forEach(m => {
                dbFinanceiro[m] = {};
                for(let d = 1; d <= 30; d++) {
                    dbFinanceiro[m][d] = [];
                }
            });

            // --- SISTEMA DE MÁSCARAS EM TEMPO REAL ---
            function configurarMascaras() {
                // Máscara Dinâmica de Dinheiro
                document.querySelectorAll('.mask-moeda').forEach(input => {
                    input.addEventListener('input', (e) => {
                        let valor = e.target.value.replace(/\D/g, "");
                        if (valor === "" || valor === "0") valor = "0";
                        valor = (parseInt(valor) / 100).toFixed(2);
                        e.target.value = formatarNumeroParaBRL(parseFloat(valor));
                    });
                });

                // Máscara Dinâmica de Quantidades Inteiras
                document.querySelectorAll('.mask-qtd').forEach(input => {
                    input.addEventListener('input', (e) => {
                        let valor = e.target.value.replace(/\D/g, "");
                        if (valor === "") valor = "0";
                        e.target.value = parseInt(valor).toLocaleString('pt-BR');
                    });
                });
            }

            function formatarNumeroParaBRL(numero) {
                return numero.toLocaleString('pt-BR', { minimumFractionDigits: 2, maximumFractionDigits: 2 });
            }

            function formatarQtd(numero) {
                return numero.toLocaleString('pt-BR');
            }

            function converterParaFloat(valorString) {
                if (typeof valorString === 'number') return valorString;
                if (!valorString) return 0;
                let limpo = valorString.replace(/\./g, "").replace(",", ".");
                return parseFloat(limpo) || 0;
            }

            configurarMascaras();

            // 1. Atualizar e Renderizar os Cards da Tela Inicial com as Mídias de Metas
            function atualizarCardsDosMeses() {
                monthsGrid.innerHTML = '';
                meses.forEach(mes => {
                    const card = document.createElement('div');
                    card.classList.add('month-card');
                    
                    let tConsorcio = 0, tSeguro = 0, tInvest = 0, tCredito = 0, tContas = 0, tVisitas = 0;

                    // Somando produção do mês
                    for (let d = 1; d <= 30; d++) {
                        dbFinanceiro[mes][d].forEach(item => {
                            tConsorcio += item.consorcio || 0;
                            tSeguro += item.seguro || 0;
                            tInvest += item.investimentos || 0;
                            tCredito += item.credito || 0;
                            tContas += item.contas || 0;
                            tVisitas += item.visitas || 0;
                        });
                    }

                    // Baselines mensais (Meta Ano / 12)
                    const mC = converterParaFloat(metaAnoConsorcio.value) / 12 || 1;
                    const mS = converterParaFloat(metaAnoSeguro.value) / 12 || 1;
                    const mI = converterParaFloat(metaAnoInvest.value) / 12 || 1;
                    const mCr = converterParaFloat(metaAnoCredito.value) / 12 || 1;
                    const mCt = converterParaFloat(metaAnoContas.value) / 12 || 1;
                    const mV = converterParaFloat(metaAnoVisitas.value) / 12 || 1;

                    // Porcentagem individual por canal
                    const pC = Math.min((tConsorcio / mC) * 100, 100);
                    const pS = Math.min((tSeguro / mS) * 100, 100);
                    const pI = Math.min((tInvest / mI) * 100, 100);
                    const pCr = Math.min((tCredito / mCr) * 100, 100);
                    const pCt = Math.min((tContas / mCt) * 100, 100);
                    const pV = Math.min((tVisitas / mV) * 100, 100);

                    // Média aritmética geral do mês
                    const mediaGeral = ((pC + pS + pI + pCr + pCt + pV) / 6).toFixed(1);

                    card.innerHTML = `
                        <div>${mes}</div>
                        <span class="month-percentage">${mediaGeral}%</span>
                    `;
                    
                    card.addEventListener('click', () => abrirMes(mes));
                    monthsGrid.appendChild(card);
                });
            }

            // Ouvintes para recalcular os cards da home se as metas do ano mudarem
            [metaAnoConsorcio, metaAnoSeguro, metaAnoInvest, metaAnoCredito, metaAnoContas, metaAnoVisitas].forEach(input => {
                input.addEventListener('input', atualizarCardsDosMeses);
            });

            // Inicialização Inicial da Home
            atualizarCardsDosMeses();

            // 2. Navegação: Abrir Mês
            function abrirMes(mes) {
                selectedMonth = mes;
                monthView.style.display = 'none';
                dayView.style.display = 'block';
                dayViewTitle.textContent = `Competência: ${mes}`;
                
                // Divisões proporcionais exatas por 12
                metaConsorcioInput.value = formatarNumeroParaBRL(converterParaFloat(metaAnoConsorcio.value) / 12);
                metaSeguroInput.value = formatarNumeroParaBRL(converterParaFloat(metaAnoSeguro.value) / 12);
                metaInvestInput.value = formatarNumeroParaBRL(converterParaFloat(metaAnoInvest.value) / 12);
                metaCreditoInput.value = formatarNumeroParaBRL(converterParaFloat(metaAnoCredito.value) / 12);
                metaContasInput.value = formatarQtd(Math.round(converterParaFloat(metaAnoContas.value) / 12));
                metaVisitasInput.value = formatarQtd(Math.round(converterParaFloat(metaAnoVisitas.value) / 12));
                
                renderizarDias();
                calcularMetasDoMes();
            }

            function renderizarDias() {
                daysGrid.innerHTML = '';
                for (let i = 1; i <= 30; i++) {
                    const cell = document.createElement('div');
                    cell.classList.add('day-cell');
                    cell.textContent = i;
                    
                    const totalLancamentos = dbFinanceiro[selectedMonth][i].length;
                    if (totalLancamentos > 0) {
                        cell.classList.add('has-data');
                        const badge = document.createElement('span');
                        badge.classList.add('badge-count');
                        badge.textContent = totalLancamentos;
                        cell.appendChild(badge);
                    }

                    cell.addEventListener('click', () => abrirDia(i));
                    daysGrid.appendChild(cell);
                }
            }

            // 3. Navegação: Abrir o Dia Selecionado
            function abrirDia(dia) {
                selectedDay = dia;
                dayView.style.display = 'none';
                formView.style.display = 'block';
                formTitle.textContent = `${selectedMonth} - Dia ${dia}`;

                cancelarEdicao();
                atualizarTabelaDoDia();
            }

            function atualizarTabelaDoDia() {
                lancamentosTableBody.innerHTML = '';
                const registros = dbFinanceiro[selectedMonth][selectedDay];

                if(registros.length === 0) {
                    lancamentosTableBody.innerHTML = `<tr><td colspan="8" style="text-align:center; color:#94a3b8;">Nenhum lançamento realizado neste dia.</td></tr>`;
                    return;
                }

                registros.forEach((reg, index) => {
                    const tr = document.createElement('tr');
                    tr.innerHTML = `
                        <td><strong>${reg.cliente}</strong></td>
                        <td>R$ ${formatarNumeroParaBRL(reg.consorcio)}</td>
                        <td>R$ ${formatarNumeroParaBRL(reg.seguro)}</td>
                        <td>R$ ${formatarNumeroParaBRL(reg.investimentos)}</td>
                        <td>R$ ${formatarNumeroParaBRL(reg.credito)}</td>
                        <td>${formatarQtd(reg.contas)}</td>
                        <td>${formatarQtd(reg.visitas)}</td>
                        <td>
                            <button class="btn-action btn-edit" onclick="editarRegistro(${index})">Editar</button>
                            <button class="btn-action btn-delete" onclick="deletarRegistro(${index})">Excluir</button>
                        </td>
                    `;
                    lancamentosTableBody.appendChild(tr);
                });
            }

            // 4. Edição e Remoção de Clientes
            window.editarRegistro = function(index) {
                const reg = dbFinanceiro[selectedMonth][selectedDay][index];
                
                document.getElementById('cliente').value = reg.cliente;
                document.getElementById('consorcio').value = formatarNumeroParaBRL(reg.consorcio);
                document.getElementById('seguro').value = formatarNumeroParaBRL(reg.seguro);
                document.getElementById('investimentos').value = formatarNumeroParaBRL(reg.investimentos);
                document.getElementById('credito').value = formatarNumeroParaBRL(reg.credito);
                document.getElementById('contas').value = formatarQtd(reg.contas);
                document.getElementById('visitas').value = formatarQtd(reg.visitas);
                
                editingIndex = index;
                formSectionTitle.textContent = "Editar Lançamento";
                submitBtn.textContent = "Salvar Alterações";
                submitBtn.style.backgroundColor = "#3b82f6";
                document.getElementById('cliente').focus();
            };

            window.deletarRegistro = function(index) {
                if(confirm("Tem certeza que deseja remover este lançamento?")) {
                    dbFinanceiro[selectedMonth][selectedDay].splice(index, 1);
                    atualizarTabelaDoDia();
                    calcularMetasDoMes();
                }
            };

            function cancelarEdicao() {
                editingIndex = null;
                financeForm.reset();
                document.getElementById('consorcio').value = "0,00";
                document.getElementById('seguro').value = "0,00";
                document.getElementById('investimentos').value = "0,00";
                document.getElementById('credito').value = "0,00";
                document.getElementById('contas').value = "0";
                document.getElementById('visitas').value = "0";
                formSectionTitle.textContent = "Novo Lançamento";
                submitBtn.textContent = "Adicionar Lançamento";
                submitBtn.style.backgroundColor = "#10b981";
            }

            // 5. Motor de Processamento das Metas Proporcionais
            function calcularMetasDoMes() {
                let totalConsorcio = 0, totalSeguro = 0, totalInvest = 0, totalCredito = 0, totalContas = 0, totalVisitas = 0;

                for (let d = 1; d <= 30; d++) {
                    dbFinanceiro[selectedMonth][d].forEach(item => {
                        totalConsorcio += item.consorcio || 0;
                        totalSeguro += item.seguro || 0;
                        totalInvest += item.investimentos || 0;
                        totalCredito += item.credito || 0;
                        totalContas += item.contas || 0;
                        totalVisitas += item.visitas || 0;
                    });
                }

                realizadoConsorcio.textContent = `R$ ${formatarNumeroParaBRL(totalConsorcio)}`;
                realizadoSeguro.textContent = `R$ ${formatarNumeroParaBRL(totalSeguro)}`;
                realizadoInvest.textContent = `R$ ${formatarNumeroParaBRL(totalInvest)}`;
                realizadoCredito.textContent = `R$ ${formatarNumeroParaBRL(totalCredito)}`;
                realizadoContas.textContent = formatarQtd(totalContas);
                realizadoVisitas.textContent = formatarQtd(totalVisitas);

                const mConsorcio = converterParaFloat(metaConsorcioInput.value) || 1;
                const mSeguro = converterParaFloat(metaSeguroInput.value) || 1;
                const mInvest = converterParaFloat(metaInvestInput.value) || 1;
                const mCredito = converterParaFloat(metaCreditoInput.value) || 1;
                const mContas = converterParaFloat(metaContasInput.value) || 1;
                const mVisitas = converterParaFloat(metaVisitasInput.value) || 1;

                const pConsorcio = Math.min((totalConsorcio / mConsorcio) * 100, 100).toFixed(1);
                const pSeguro = Math.min((totalSeguro / mSeguro) * 100, 100).toFixed(1);
                const pInvest = Math.min((totalInvest / mInvest) * 100, 100).toFixed(1);
                const pCredito = Math.min((totalCredito / mCredito) * 100, 100).toFixed(1);
                const pContas = Math.min((totalContas / mContas) * 100, 100).toFixed(1);
                const pVisitas = Math.min((totalVisitas / mVisitas) * 100, 100).toFixed(1);

                barConsorcio.style.width = `${pConsorcio}%`;
                txtConsorcio.textContent = `${pConsorcio}%`;

                barSeguro.style.width = `${pSeguro}%`;
                txtSeguro.textContent = `${pSeguro}%`;

                barInvest.style.width = `${pInvest}%`;
                txtInvest.textContent = `${pInvest}%`;

                barCredito.style.width = `${pCredito}%`;
                txtCredito.textContent = `${pCredito}%`;

                barContas.style.width = `${pContas}%`;
                txtContas.textContent = `${pContas}%`;

                barVisitas.style.width = `${pVisitas}%`;
                txtVisitas.textContent = `${pVisitas}%`;
            }

            // 6. Manipulação de Envio do Formulário
            financeForm.addEventListener('submit', (e) => {
                e.preventDefault();

                const dadosLancamento = {
                    cliente: document.getElementById('cliente').value,
                    consorcio: converterParaFloat(document.getElementById('consorcio').value),
                    seguro: converterParaFloat(document.getElementById('seguro').value),
                    investimentos: converterParaFloat(document.getElementById('investimentos').value),
                    credito: converterParaFloat(document.getElementById('credito').value),
                    contas: converterParaFloat(document.getElementById('contas').value),
                    visitas: converterParaFloat(document.getElementById('visitas').value)
                };

                if (editingIndex !== null) {
                    dbFinanceiro[selectedMonth][selectedDay][editingIndex] = dadosLancamento;
                    alert("Lançamento atualizado com sucesso!");
                } else {
                    dbFinanceiro[selectedMonth][selectedDay].push(dadosLancamento);
                }

                cancelarEdicao();
                atualizarTabelaDoDia();
            });

            // Botões de Voltar
            backToMonthsBtn.addEventListener('click', () => {
                dayView.style.display = 'none';
                monthView.style.display = 'block';
                atualizarCardsDosMeses();
            });

            backToDaysBtn.addEventListener('click', () => {
                formView.style.display = 'none';
                dayView.style.display = 'block';
                renderizarDias();
                calcularMetasDoMes();
            });
        });
    </script>
</body>
</html>
