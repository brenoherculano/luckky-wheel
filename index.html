<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Luckyy</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
</head>
<body class="bg-black text-light">
    <!-- Modal -->
    <div class="modal fade" id="itemsListModal" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered">
            <div class="modal-content bg-dark text-light">
                <div class="modal-header">
                    <div class="col text-center">
                        <h5 class="modal-title" id="staticBackdropLabel">☘️</h5>
                    </div>
                </div>
                <div class="modal-body text-start">
                    <table class="table table-hover table-dark">
                        <thead>
                            <tr>
                                <th class="col-11"></th>
                                <th class="col-1"></th>
                            </tr>
                        </thead>
                        <tbody id="itemsTable">
                            <tr>
                                <td class="item" contenteditable="true">A Vida Invisível (2019)</td>
                                <td>
                                    <button type="button" class="removeItemBtn btn btn-sm">❌</button>
                                </td>
                            </tr>
                            <tr>
                                <td class="item" contenteditable="true">O Sol na Cabeça (2018)</td>
                                <td>
                                    <button type="button" class="removeItemBtn btn btn-sm">❌</button>
                                </td>
                            </tr>
                            <tr>
                                <td class="item" contenteditable="true">Praia do Futuro (2014)</td>
                                <td>
                                    <button type="button" class="removeItemBtn btn btn-sm">❌</button>
                                </td>
                            </tr>
                            <tr>
                                <td class="item" contenteditable="true">O Abismo Prateado (2011)</td>
                                <td>
                                    <button type="button" class="removeItemBtn btn btn-sm">❌</button>
                                </td>
                            </tr>
                            <tr>
                                <td class="item" contenteditable="true">Viajo proque preciso, volto porque te amo (2009)</td>
                                <td>
                                    <button type="button" class="removeItemBtn btn btn-sm">❌</button>
                                </td>
                            </tr>
                            <tr>
                                <td class="item" contenteditable="true">O Céu de Suely (2006)</td>
                                <td>
                                    <button type="button" class="removeItemBtn btn btn-sm">❌</button>
                                </td>
                            </tr>
                            <tr>
                                <td class="item" contenteditable="true">Madame Satã (2002)</td>
                                <td>
                                    <button type="button" class="removeItemBtn btn btn-sm">❌</button>
                                </td>
                            </tr>
                            <tr id="newItemTr">
                                <td id="newItem" class="link-secondary" contenteditable="true">Adicionar</td>
                                <td>
                                    <button id="addItemBtn" type="button" class="btn btn-sm link-primary">➕</button>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="modal-footer">
                    <div class="col text-center">
                        <button id="readyBtn" type="button" class="btn btn-success" data-bs-dismiss="modal">Pronto!</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Wheel -->
    <div id="wheel"></div>
</body>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa" crossorigin="anonymous"></script>
<script>

    // Dispara modal ao carregar página
    const itemsListModal = new bootstrap.Modal('#itemsListModal');

    itemsListModal.show();

    // Função para remover item
    function setRemoveItemListener() {
        const removeItemBtns = document.getElementsByClassName('removeItemBtn');

        for (let index = 0; index < removeItemBtns.length; index++) {
            let removeBtn = removeItemBtns[index];

            removeBtn.addEventListener('click', function (e) {
                e.target.parentNode.parentNode.remove();
            })
        }
    }

    setRemoveItemListener();

    // Função para limpar placeholder
    const addItemField = document.getElementById('newItem');

    addItemField.addEventListener('focusin', () => {
        addItemField.innerText = '';
    })

    // Função para adcionar item via btn
    const addItemBtn = document.getElementById('addItemBtn');

    addItemBtn.addEventListener('click', () => {
        let tr = document.createElement('tr');
        let tdItemName = document.createElement('td');
        let tdBtn = document.createElement('td');
        let btn = document.createElement('button');

        btn.type = 'button';
        btn.className = 'removeItemBtn btn btn-sm';
        btn.innerText = '❌';

        tdItemName.className = 'item';
        tdItemName.setAttribute('contenteditable', 'true');
        tdItemName.innerText = addItemField.innerHTML;

        tdBtn.appendChild(btn);
        tr.appendChild(tdItemName);
        tr.appendChild(tdBtn);

        document.getElementById('itemsTable').insertBefore(tr,document.getElementById('newItemTr'));
        setRemoveItemListener();
        addItemField.innerText = 'Adicionar';
    });

    // Funcção para carregar os itens para a roda
    document.getElementById('readyBtn').addEventListener('click', () => {
        const items = document.getElementsByClassName('item');
        const wheel = document.getElementById('wheel')

        for (let index = 0; index < items.length; index++) {
            let item = items[index];
            
            let wheelContent = document.createElement('p');
            wheelContent.innerHTML = item.innerText;

            wheel.appendChild(wheelContent);
        }
    })
</script>
</html>