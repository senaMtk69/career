# career
career fields

# Installations
//Version: 1.0

import { Career, Field,} from 'career-field';

# Data

var positionData = {

'PositionName': {
  
        'Technology & IT': [
    'name': 'IT Systems Assistant',
    'name': 'IT Support Technician',
    'name': 'Junior Web Development',
    'name': 'Help Desk Assistant'
    ],
    
        'Marketing & Sales': [
    'name': 'Junior Marketing Coordinator',
    'name': 'Sales Associate',
    'name': 'Junior Content Creator',
    'name': 'Social Media Assistant',
    'name': 'Marketing Assistant',
    'name': 'Sales Development Representative', 
    'name': 'Member Marketing', 
    'name': 'Certificate Validator'
    ], 
    
    'Finance & Accounting': [
    'name': 'Finance Assistant',
    'name': 'Financial Analyst Trainee',
    'name': 'Junior Auditor',
    'name': 'Accounts Payable Clerk',
    'name': 'Junior Bookkeeper',
    'name': 'Payroll Assistant',
    'name': 'Junior Tax Analyst',
    'name': 'Trainee Account Assistant'
    ], 
    'Human Resources': ['HR Assistant', 'Junior Recruiter', 'Talent Acquisition Coordinator', 'HR Coordinator', 'Training Assistant'],
    'Operations & Logistics': ['Operations Assistant', 'Junior Project Coordinator', 'Supply Chain Assistant', 'Logistics Coordinator', 'Procurement Assistant', 'Warehouse Associate'],
    'Healthcare': ['Junior Medical Assistant', 'Healthcare Assistant', 'Pharmacy Technician', 'Junior Healthcare Administrator'], 
    'Education': ['Teachers Assistant', 'Administrative Assistant', 'Admissions Assistant', 'Library Assistant', 'Curriculum Coordinator'],
    'Creative & Design': ['Junior Graphic Designer', 'Creative Assistant', 'Junior Video Editor', 'Social Media Content Designer'],
    'Customer Service': ['Customer Service Assistant', 'Call Center Representative', 'Junior Client Relations Specialist', 'Technical Support Assistant', 'Customer Success Coordinator', 'Junior Help Desk Support'],
    'Engineering': ['Junior Mechanical Engineer', 'Junior Electrical Engineer', 'Engineering Technician', 'Junior Quality Assurance Engineer', 'Drafting Technician', 'Sheetmetal engineer', 'Artisan Assistant'],
    'Administration': ['Administrative Assistant', 'Trainee Scanner', 'Trainee Admin Assistant', 'Trainee Marketing Assistant', 'Office Coordinator'],


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
