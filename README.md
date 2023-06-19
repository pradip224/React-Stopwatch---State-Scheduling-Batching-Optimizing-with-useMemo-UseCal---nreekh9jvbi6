# React Stopwatch

This is a simple stopwatch application built using React and the `useRef` hook. It allows you to start, stop, lap, and reset the stopwatch time.
![home](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/f6faca6e-7bbb-4e14-917c-35bc8eae9ddd)

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
![start](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/bb08a812-acfb-40f2-902f-467bf3b6f372)

- **STOP**: Clicking the "STOP" button will stop the stopwatch time. The time on the screen will freeze until you start it again.
![stop](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/b86c5015-0798-4f31-b433-c098375873a4)

- **LAP**: Clicking the "LAP" button will show the lap time and append it to the section with the class "laps". The lap section will only be visible when you click the "LAP" button and a lap time is added.
![laps](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/8cb17006-a61e-42fc-ae4b-70564153de93)

- **RESET**: Clicking the "RESET" button will reset the stopwatch time to its initial value, which is 0.000 (up to 3 decimal places).
![reset](https://github.com/pradip224/React-Stopwatch---State-Scheduling-Batching-Optimizing-with-useMemo-UseCal---nreekh9jvbi6/assets/122960934/1888d82a-7fe5-47e1-b1c4-78bd20b6daa1)

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
