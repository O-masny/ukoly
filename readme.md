function overitFormular() {
    let input = document.getElementById('email').value;
    if (!input.includes('@')) {
        alert('Neplatný email!');
        return false;
    }
    return true;
}

// vytvoř další 2 funkce
