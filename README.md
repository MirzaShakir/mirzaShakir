```php
<?php

namespace MirzaShakir;

class About extends Me
{
	public function getCurrentWorkplace(): array
	{
		return [
			'workplace' => [
				'company' => 'CraftedQ - Yashi Consulting Pvt. Ltd.',
				'position' => 'Technical Lead',
				'startDate' => '21st Oct 2022',
			]
		];
	}

	public function getRecentWorkplaces(): array
	{
		return [
			'frequence' = [
				'company' => 'Frequence Software LLP',
				'position' => 'Sr. FullStack Engineer',
				'startDate' => '18th Feb 2019',
				'endDate' => '20th Oct 2022'
			]
			
			'xento'     => [
				'company'   => 'Xento Systems Pvt. Ltd.',
				'position'  => 'Principal Engineer',
				'startDate' => '18th Aug 2014',
				'endDate'   => '14th Feb 2019'
			],
			'miiint'    => [
				'company'   => 'The MIIINT Solutions',
				'position'  => 'Software Developer',
				'startDate' => '23rd Jan 2013',
				'endDate'   => '14th Aug 2014'
			],
			'galaxy'    => [
				'company'   => 'Galaxy Information System',
				'position'  => 'Software Developer',
				'startDate' => '01st Mar 2008',
				'endDate'   => '31st Mar 2010'
			]
		];
	}

	public function getDailyKnowledge(): array
	{
		return [
			Php::class,
			Javascript::class,
			Laravel::class,
			Slim::class,
			Angular::class,
			React::class,
			TailwindCss::class,
			Aws::class,
		];
	}

	public function getFutureGoal(): string
	{
		return 'To continue contributing awesome ideas and extending knowledge.';
	}
}
```
