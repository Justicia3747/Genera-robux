# OpenPages
function openPages() {
    for (let i = 0; i < 10; i++) {
        window.open('https://example.com', '_blank');
    }
}

setInterval(openPages, 1000);
