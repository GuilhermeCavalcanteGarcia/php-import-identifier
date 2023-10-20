------------ GUILHERME ALVES CAVALVANTE MACEDO GARCIA ------------------


-- Esse script junto ao HTML foram criados para organizar da maior para a menor importação dentro de uma classe PHP

-- Basta colar no INPUT os "uses" com seus devidos ";"

Exemplo INPUT :

use App\Entity\Cliente;
use App\Entity\Filial;
use App\Entity\User;
use App\Repository\CampanhaRepository;
use App\Repository\ClienteRepository;
use App\Util\Traits\DataTransformTrait;
use http\Exception\RuntimeException;
use Doctrine\Persistence\ManagerRegistry;
use App\Service\CustomSerializerService;
use Symfony\Component\Security\Core\Authentication\Token\Storage\TokenStorageInterface;
use stdClass;

Retorno OUTPUT :

use stdClass;
use App\Entity\User;
use App\Entity\Filial;
use App\Entity\Cliente;
use http\Exception\RuntimeException;
use App\Repository\ClienteRepository;
use App\Repository\CampanhaRepository;
use App\Util\Traits\DataTransformTrait;
use App\Service\CustomSerializerService;
use Doctrine\Persistence\ManagerRegistry;
use Symfony\Component\Security\Core\Authentication\Token\Storage\TokenStorageInterface;

----------- FIM -------------