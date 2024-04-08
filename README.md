```js
class ThieuTrungKien {}

class Attributes extends ThieuTrungKien {
    constructor() {
        super();
        this.contact = () => ({
            facebook: "https://www.facebook.com/ThieuTrungKi3n",
            email: "ttk.trungkien333@gmail.com"
        });

        this.life = () => ({
            spokenLanguages: ['Vietnamese', 'English'],
            age: 19
        });

        this.coding = () => ({
            programmingLanguages: {
                expert: ['python', 'js', 'c++'],
                intermediate: ['go'],
                learning: ['c#', 'asm', 'java']
            },
            ide: ['vscode']
        });
    }
}
```
