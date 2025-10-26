# ¿Que hace quien te quiere?

<p id="textToCopy">gtnyfp1qufYG-5_KUZ9NR5pzfRFT7XoxhEpKHVTYJ2Nle-Qn7sqquhxbaUHKmlN7aQmTNBtxenrlBNxmSSckRzqNFnbeFDeahSfCOZgfdmw</p>
<button id="copyButton">Copiar</button>

<script>
document.getElementById('copyButton').addEventListener('click', async () => {
    const text = document.getElementById('textToCopy').innerText;
    try {
        await navigator.clipboard.writeText(text);
        // alert('Text copied to clipboard!');
    } catch (err) {
        console.error('Failed to copy text: ', err);
        alert('Failed to copy text.');
    }
});
</script>
