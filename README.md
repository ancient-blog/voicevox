# voicevox

## Inputs

| Name | Description | Default Value | Required | Type |
| -------------- | ------------------------------------------------------------------------------------------------------------------- | --------------------------------- | -------- | ------- |
| speaker        | Selection of VOICEVOX speaker. Each speaker has distinct voice qualities and characteristics.                    | '1'                               | No       | String  |
| source         | Path to the folder containing text files from which audio data will be generated.                                | '${{ github.workspace }}/text' | Yes       | String  |
| destination    | Path to the folder where the generated audio data will be stored.                                                   | '${{ github.workspace }}/artifact' | No       | String  |

## Outputs

This action doesn't produce any outputs.

## Example Usage

# License

The scripts and documentation in this project are released under the [BSD 2-Clause License](LICENSE)