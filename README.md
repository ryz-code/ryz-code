### HELLO 👋

![](https://visitor-badge.glitch.me/badge?page_id=ryz-code.ryz-code)

```php
<?php
namespace RyzXD;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Ryz-Team',
                'position' => 'Founder'         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            my::class,
        ];
    }
    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
