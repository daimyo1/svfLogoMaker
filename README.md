![logo](https://github.com/user-attachments/assets/f6b94dcb-1826-4d43-bf37-cca9e4798365)# SVG Logo Maker

## Description

The SVG Logo Maker is a Node.js command-line application that takes user input to generate a logo and save it as an SVG file. This tool is designed for freelance web developers who need a simple logo for their projects without the need to hire a graphic designer.

## User Story

AS a freelance web developer  
I WANT to generate a simple logo for my projects  
SO THAT I don't have to pay a graphic designer  

## Acceptance Criteria

- GIVEN a command-line application that accepts user input
  - WHEN I am prompted for text
    - THEN I can enter up to three characters
  - WHEN I am prompted for the text color
    - THEN I can enter a color keyword (OR a hexadecimal number)
  - WHEN I am prompted for a shape
    - THEN I am presented with a list of shapes to choose from: circle, triangle, and square
  - WHEN I am prompted for the shape's color
    - THEN I can enter a color keyword (OR a hexadecimal number)
  - WHEN I have entered input for all the prompts
    - THEN an SVG file is created named `logo.svg` AND the output text "Generated logo.svg" is printed in the command line
  - WHEN I open the `logo.svg` file in a browser
    - THEN I am shown a 300x200 pixel image that matches the criteria I entered

## Mock-Up

![U<svg width="300" height="200" xmlns="http://www.w3.org/2000/svg">
            <circle cx="150" cy="100" r="80" fill="GREEN" />
            <text x="150" y="125" font-size="60" text-anchor="middle" fill="WHITE">SVG</text>
        </svg>ploading logo.svg…]()

 Video Link- https://drive.google.com/file/d/1bEt7KFqSF1lBgmkvM30LmvXW4bvi1Blo/view


## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/daimyo1/svgLogoMaker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd svglogoMaker
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Install Inquirer and Jest:
    ```bash
    npm install inquirer jest
    ```

### Usage

1. Run the application:
    ```bash
    node index.js
    ```

2. Follow the prompts to generate your logo:
    - Enter up to three characters for the logo text.
    - Enter a color keyword or hexadecimal number for the text color.
    - Choose a shape for the logo: Circle, Triangle, or Square.
    - Enter a color keyword or hexadecimal number for the shape color.

3. The generated SVG file will be saved in the `examples` folder with the name `logo.svg`.

## Tests

The application includes Jest tests for the shape classes. To run the tests, use the following command:
```bash
npm test# svfLogoMaker
