import csv

def mask_string(string):
    if len(string) < 3:
        return None
    else:
        return string[:2] + '*' * (len(string) - 4) + string[-2:]

def mask_file(input_file, output_file):
    with open(input_file, 'r') as f_input:
        with open(output_file, 'w', newline='') as f_output:
            csv_writer = csv.writer(f_output)
            for line in f_input:
                line = line.strip()
                if len(line) >= 3:
                    masked_line = mask_string(line)
                    if masked_line:
                        csv_writer.writerow([masked_line])

input_file = input('input file name: ')
output_file = 'output.csv'
mask_file(input_file, output_file)
print("File di output CSV creato con successo:", output_file)
