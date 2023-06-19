# React Stopwatch

This is a simple stopwatch application built using React and the `useRef` hook. It allows you to start, stop, lap, and reset the stopwatch time.
![home](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/8b793882-b19e-42e0-9078-ad556502c294)

## Getting Started

To get started with the stopwatch application, follow the instructions below.

### Prerequisites

Make sure you have the following software installed on your system:

- Node.js (version 12 or higher)
- npm (version 6 or higher)

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6.git
```

2. Navigate to the project directory:

```bash
cd react-stopwatch
```

3. Install the dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm start
```

5. Open your browser and visit `http://localhost:3000` to view the stopwatch application.

## Usage

The stopwatch application provides the following features:

- **START**: Clicking the "START" button will start the stopwatch time. The time on the screen will be updated every 10 milliseconds.
![start](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/adedc68f-1ade-428f-a628-60bfff754b46)

- **STOP**: Clicking the "STOP" button will stop the stopwatch time. The time on the screen will freeze until you start it again.
![stop](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/bc2a00dd-fb68-4434-a99e-6c66b8186a1c)

- **LAP**: Clicking the "LAP" button will show the lap time and append it to the section with the class "laps". The lap section will only be visible when you click the "LAP" button and a lap time is added.
![laps](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/fc81b0da-2931-4cac-b2aa-35cf62925193)

- **RESET**: Clicking the "RESET" button will reset the stopwatch time to its initial value, which is 0.000 (up to 3 decimal places).
![reset](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/89b3f67e-cb15-41dd-80aa-557fffc81a10)

## Implementation Details

The stopwatch application is implemented using a combination of state and `useRef` hook. The `useRef` hook is used to store the interval reference, which allows us to stop the interval by clicking the button.

The initial stopwatch time is set to 0.000 (up to 3 decimal places). The time on the screen is updated every 10 milliseconds.

## Contributing

Contributions to this stopwatch application are welcome! If you find any issues or want to enhance the functionality, please submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This stopwatch application is built using React and the `useRef` hook. Special thanks to the React community for providing the necessary tools and resources to develop this project.

If you have any questions or need further assistance, feel free to contact us.
