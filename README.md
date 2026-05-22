buttonStart.setOnClickListener {
    statusText.text = "System ON 🚀 Motors activated"
}

buttonStop.setOnClickListener {
    statusText.text = "System OFF 🛑 Motors stopped"
}

buttonStatus.setOnClickListener {
    statusText.text = "System is stable ✔ Ready"
}