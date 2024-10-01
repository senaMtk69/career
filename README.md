# career
career fields

# Installations
//Version: 1.0

import { Career, Field,} from 'career-field';

# Usage

//To get a certain career & it's field

        $w('#dropdownCareer').options = .map(() => ({
            label: career.name,
            value: career.isoCode
        }))
        
        $w('#dropdownField').options = .map(() => ({
            label: .name,
            value: isoCode
        }))

export function dropdownCareer_change(event) {
    const  = event.target.value;
    ()

    $w('#dropdownField').value = undefined;
}
