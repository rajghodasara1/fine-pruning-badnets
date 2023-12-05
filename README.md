# fine-pruning-badnets

The presence of successful backdoor attacks on Deep Neural Networks (DNNs) indicates that these networks possess excess learning capacity. Specifically, DNNs can learn to provide incorrect responses to inputs containing a backdoor, while still maintaining accurate responses to clean inputs. This phenomenon revolves around specific neurons within the network known as "backdoor neurons," which the attack subtly manipulates to identify backdoors and induce misbehavior.

Within this laboratory study, our focus is on assessing a defense technique aimed at potentially neutralizing a backdoor by eliminating neurons that remain dormant when processing clean inputs. This defensive strategy is coined as the "pruning defense."

## Usage

1. Clone the repository
      ```bash
      git clone git@github.com:utsavoza/badnets.git
      ```

2. Download the validation and test datasets from [here](https://drive.google.com/drive/folders/1Rs68uH8Xqa4j6UxG53wzD0uyI8347dSq?usp=sharing) and place them under `data/` directory.

3. Create and activate the virtual environment
      ```bash
      python -m venv venv
      source venv/bin/activate
      ```

4. Install the required dependencies
      ```bash
      pip install -r requirements.txt
      ```

5. Run this command to start an ipython kernel with the virtual environment.
     ```bash
     ipython kernel install --user --name=venv

6. Open Lab4.ipynb, select kernel venv and run to reproduce code.

## LICENSE
This project is licensed under MIT License. See [LICENSE](./LICENSE).
