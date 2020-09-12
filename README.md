``` typescript
@Bio( {
    name: 'Amila Kanchana',
    description: 'A developer',
    linkedInUrl: 'www.linkedin.com/amilakanchana0',
    facebookUrl: 'www.facebook.com/amilakanchana0'
} )
export class AmilaKanchana {

    type: string = 'Full stack development';
    
    technologies: any = {
    
        frontEnd: [
            'Angular',
            'Flutter',
            'Ionic',
            'HTML/CSS'
        ],
        backEnd: [
            'NodeJs',
            'ExpressJs',
            '.Net',
            'Flask',
            'SQL',
        ],
        other: [
            'Android Studio',
            'OpenCV',
            'IOT'
        ]
    };

    experiance: string[] = [
        'Trainee - 8 Months',
        'Associate software engineer - 1 Year',
        'Software engineer - 6 months', // current
    ]
    constructor () {

    }

}

```
