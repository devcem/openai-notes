$route['last_logins'] = function($db, $form = array()){
    $last_logins = $db->select('accounts', '', 'username, last_login, created_at', ' ORDER BY last_login DESC LIMIT 100');

    $last_logins = array_map(function($last_login){
        $last_login['country'] = get_country($last_login['last_login']);
        return $last_login;
    }, $last_logins);

    var_dump($last_logins);

    return array('success' => true, 'last_logins' => $last_logins);
};

"""
which new functions added to the implementation?
Answer: get_country