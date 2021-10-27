import { contact, IUser } from './github'

export default class ME implements IUser {
    public static firstName = 'Power'
    public static lastName = 'null'
    public static username = 'ThePower666'
    public static website = 'None'
    public static aliases = ['power']
    public static skills = ['TypeScript', 'JavaScript', 'NodeJS', 'C', 'EJS', 'Express', 'NoSQL', 'CSS', 'HTML']
    public static info = {
        age: 20,
        country: 'Japan',
        org: 'None',
        likes: ['Zelda', 'Death note', 'Well.....'],
        hobbies: ['Program', 'To Smoke', 'Listen To Music'],
        reach: [
            {
                name: contact.WhatsApp,
                url: 'https://wa.me/+359988883454?text=Well...'
            }
        ]
    }
    public static projects = [
        {
            name: 'Power',
            homepage: 'https://github.com/ThePower666/_Power_/README.md',
            repo: 'https://github.com/ThePower666',
            language: ['JavaScript', 'TypeScript'],
            ongoing: true,
            status: 'privated'
        
        }
    ]
}


