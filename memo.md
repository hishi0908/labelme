 - py -3.12 -m venv venv
 - .\venv\Scripts\Activate.ps1
 - pip install labelme
 - pip install labelme2yolo

--------
 labelme2yolo --help

    Convert LabelMe JSON to YOLO format
    Usage: labelme2yolo.exe [OPTIONS] --json_dir <JSON_DIR> 
    [LABEL_LIST]...
    Arguments:
    [LABEL_LIST]...
    - Options:
     - -d, --json_dir <JSON_DIR>
     -    --val_size <VAL_SIZE>            [default: 0.2]
     -   --test_size <TEST_SIZE>          [default: 0]
     -   --output_format <OUTPUT_FORMAT>  [default: bbox] [aliases: -format] [possible values: polygon, bbox]
     -   --seed <SEED>                    [default: 42]
     - -h, --help                           Print help
     - -V, --version                        Print version