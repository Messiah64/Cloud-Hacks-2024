# SustAIn

Smarter energy management and ESG reporting with AI.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

SustAIn is a smarter energy management and ESG reporting system leveraging AI to provide real-time insights and automation. This project aims to enhance energy efficiency and streamline ESG reporting for better sustainability practices.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Messiah64/Cloud-Hacks-2024.git
    cd Cloud-Hacks-2024
    ```

2. Install the required packages:
    ```bash
    pip install altair==5.3.0 \
                annotated-types==0.7.0 \
                anyio==4.4.0 \
                attrs==23.2.0 \
                blinker==1.8.2 \
                cachetools==5.3.3 \
                certifi==2024.6.2 \
                charset-normalizer==3.3.2 \
                click==8.1.7 \
                colorama==0.4.6 \
                contourpy==1.2.1 \
                cycler==0.12.1 \
                deprecation==2.1.0 \
                exceptiongroup==1.2.1 \
                filelock==3.13.1 \
                fonttools==4.53.0 \
                fsspec==2024.2.0 \
                gitdb==4.0.11 \
                GitPython==3.1.43 \
                gotrue==2.5.2 \
                h11==0.14.0 \
                httpcore==1.0.5 \
                httpx==0.27.0 \
                idna==3.7 \
                intel-openmp==2021.4.0 \
                Jinja2==3.1.3 \
                jsonschema==4.22.0 \
                jsonschema-specifications==2023.12.1 \
                kiwisolver==1.4.5 \
                markdown-it-py==3.0.0 \
                MarkupSafe==2.1.5 \
                matplotlib==3.9.0 \
                mdurl==0.1.2 \
                mkl==2021.4.0 \
                mpmath==1.3.0 \
                networkx==3.2.1 \
                numpy==1.26.3 \
                opencv-python==4.10.0.84 \
                packaging==24.1 \
                pandas==2.2.2 \
                pillow==10.2.0 \
                plotly==5.22.0 \
                postgrest==0.16.8 \
                protobuf==5.27.1 \
                psutil==6.0.0 \
                py-cpuinfo==9.0.0 \
                pyarrow==16.1.0 \
                pydantic==2.7.4 \
                pydantic_core==2.18.4 \
                pydeck==0.9.1 \
                Pygments==2.18.0 \
                pyparsing==3.1.2 \
                python-dateutil==2.9.0.post0 \
                pytz==2024.1 \
                PyYAML==6.0.1 \
                realtime==1.0.6 \
                referencing==0.35.1 \
                requests==2.32.3 \
                rich==13.7.1 \
                rpds-py==0.18.1 \
                scipy==1.13.1 \
                seaborn==0.13.2 \
                six==1.16.0 \
                smmap==5.0.1 \
                sniffio==1.3.1 \
                storage3==0.7.6 \
                streamlit==1.36.0 \
                StrEnum==0.4.15 \
                supabase==2.5.1 \
                supafunc==0.4.6 \
                sympy==1.12 \
                tbb==2021.11.0 \
                tenacity==8.4.1 \
                toml==0.10.2 \
                toolz==0.12.1 \
                torch==2.3.1+cu121 \
                torchaudio==2.3.1+cu121 \
                torchvision==0.18.1+cu121 \
                tornado==6.4.1 \
                tqdm==4.66.4 \
                typing_extensions==4.12.2 \
                tzdata==2024.1 \
                ultralytics==8.2.36 \
                ultralytics-thop==2.0.0 \
                urllib3==2.2.2 \
                watchdog==4.0.1 \
                websockets==12.0
    ```

## Usage

To use the project, follow these steps:

1. Register or log in to Supabase and get an API key.

2. Upload the code to ESP32 or ESP8266, based on requirements. Connect the RGB LED pads to pins 12, 13, 14, 15 (ESP32) or D1, D2, D3, D4 (ESP8266). Connect the servo to pin 3.

3. Ensure that the server laptop and ESP are on the same network. Add the host network IP into the Arduino code, along with the correct WiFi password and Supabase API key.

4. Start the Python server and the ESP Arduino code. Ensure that a camera view shows up of the four quadrants and test it out. Ensure the Supabase server is running and observe the peaks and lows when objects are placed in or removed.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License.

## Contact

Made by Mo, Nyan, and Kaushik. For any inquiries, please contact Kaushik at kaushikmanian456@gmail.com.
