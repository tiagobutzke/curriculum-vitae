#TIAGO BATISTA BUTZKE
##Software Engineer


```PHP
/** 
 * I really love programming
 * This is not a work, this is fun
 * 
 * @author   tiagobutzke <tiago.butzke@gmail.com>
 * @age      27 Years old
 * @twitter  @tiagobutzke
 * @github   github.com/tiagobutzke
 * @linkedin linkedin.com/in/tiagobutzke
 */
```

##Experience##
```PHP
namespace Curriculum;

use \Tiago\Experience;

$experience5 = new Experience();
$experience5->setCompany('FCamara');
$experience5->setPeriod('2013 - currently');
$experience5->setPosition('IT consultant');
$experience5->setSite('www.fcamara.com.br');
$experience5->save();


$experience4 = new Experience();
$experience4->setCompany('Stoodos');
$experience4->setPeriod('2011 - currently');
$experience4->setPosition('CEO');
$experience4->setSite('www.stoodos.com');
$experience4->save();

$experience3 = new Experience();
$experience3->setCompany('Onsee');
$experience3->setPeriod('2009 - 2011');
$experience3->setPosition('Software Engineer');
$experience3->setSite('www.ons.ee');
$experience3->save();

$experience2 = new Experience();
$experience2->setCompany('3 Up Technology');
$experience2->setPeriod('2008 - 2009');
$experience2->setPosition('Developer');
$experience2->setSite('www.ons.ee');
$experience2->save();

$experience1 = new Experience();
$experience1->setCompany('INCRA - (Brazilian Institute of Agricultural Colonization)');
$experience1->setPeriod('2008 - 2008');
$experience1->setPosition('Trainee');
$experience3->setSite('www.incra.gov.br');
$experience1->save();
```


##Skills##
```PHP
class Php
{
    public $skils = array(
        'Frameworks' => array(
            'Zend Framework' => '* * * * *',
            'Phalcon PHP'    => '* * * *',
            'Codeigniter'    => '* * * * *',
            'Laravel'        => '* * *',
            'Slim Framework' => '* * *'
        ),
        'ORM' => array(
            'Doctrine 1' => '* * * * *',
            'Doctrine 2' => '* * * * *'
        ),
        'Code Quality' => array(
            'PHPUnit' => '* * * *',
            'PHPCS'   => '* * * *',
            'PHPDoc'  => '* * * *'
        )
    );
}

class JavaScript
{
    public $skills = array(
        'Libraries' => array(
            'jQuery'  => '* * * * *',
            'Node.js' => '* *'
        )
    );
}

class ActionScript
{
    public $skills = array(
        'Frameworks' => array(
            'Flex' => '* * * *'
        )
    );
}

class FrontEnd
{
    public $skills = array(
        'Frameworks' => array(
            'Bootstrap' => '* * * *'
        )
    );
}

class ContinuousIntegration
{
    public $skills = array(
        'Build' => array(
            'Jekins' => '* * * *',
            'Phing'  => '* * * *'
        ),
        'Deploy' => array(
            'Capistrano' => '* * * *'
        ),
        'Versioning' => array(
            'Git' => '* * * * *',
            'SVN' => '* * * * *'
        ),
        'Environment' => array(
        	'Vagrant' => '* * * * *',
        	'Chef'    => '* *'
        )
    );
}

class SystemPlan
{
    public $skills = array(
        'Charts' => array(
            'UML' => '* * * * *',
            'DER' => '* * * * *'
        ),
        'Code' => array(
            'Object Orientation' => '* * * * *',
            'Design Patterns'    => '* * * *'
        ),
        'Agile' => array(
            'Scrum'    => '* * * * *',
            'Kanban'   => '* * * * *',
            'BurnDown' => '* * * * *'
        )
    );
}

class Business
{
    public $skills = array(
        'Tools' => array(
            'Business Model Canvas' => '* * * * *',
            'A/B Tests'             => '* * * * *',
            'Lean Startup'          => '* * * *'
        )
    );
}

class Database
{
    public $skills = array(
        'Relational' => array(
            'Mysql'      => '* * * * *',
            'Sql Server' => '* * * *'
        ),
        'NoSQL' => array(
            'MongoDB' => '* * *'
        )
    );
}

class Languages
{
    public $skills = array(
        'Portuguese' => array(
            'Native'
        ),
        'English' => array(
            'Reading' => '* * * * *',
            'Writing' => '* * * *',
            'Speech'  => '* *'
        )
    );
}

class OperationalSystems
{
    public $skills = array(
        'Systems' => array(
            'MacOS'   => '* * * * *',
            'Linux'   => '* * * * *',
            'Windows' => '* * *'
        )
    );
}
```


##Education##
```PHP
class TechnologySystemsForInternet extends Course implements CourseInterface
{
    const INSTITUTION = 'University Center of Pará State - CESUPA';
    const GRADUATION = '2009';
}
```
