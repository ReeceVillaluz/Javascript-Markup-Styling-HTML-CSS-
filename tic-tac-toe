document.addEventListener('DOMContentLoaded', () => {
	const squares = document.querySelectorAll('.grid div')
	const playerDisplay = document.querySelector('#player')

	let player = "playerX"

	squares.forEach(square => {
		square.addEventListener('click', clickOutcome)
	})

	function clickOutcome(e) {
		const squareArrays = Array.from(squares)
		const squareNumber = squareArrays.indexOf(e.target)
		console.log(squareNumber)
		playerDisplay.innerHTML = player

		if(player === 'playerX') {
			squares[squareNumber].classList.add('playerX')
			player = 'player0'
		}
		else {
			squares[squareNumber].classList.add('player0')			
			player = 'playerX'
		}
	}
})
