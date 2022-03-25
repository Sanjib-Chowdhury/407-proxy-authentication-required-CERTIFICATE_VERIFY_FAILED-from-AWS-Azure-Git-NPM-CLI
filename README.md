# 407-proxy-authentication-required-CERTIFICATE_VERIFY_FAILED-from-AWS-Azure-Git-NPM-CLI

Are you seeing 407 proxy authentication required or CERTIFICATE_VERIFY_FAILED from AWS/ Azure/ Git/ NPM CLI? This script helps DevOps/ Developers & Security engineers to applications like AWS CLI, AZURE CLI, Git Client etc. to work properly from behind the corporate proxy.
It helps to reslove folllowing issues:

The remote server returned an error: (407) Proxy Authentication Required." Error 

or

az login The command failed with an unexpected error. Here is the traceback: HTTPSConnectionPool(host='login.microsoftonline.com', port=443): Max retries exceeded with url: /organizations/v2.0/.well-known/openid-configuration (Caused by ProxyError('Cannot connect to proxy.', NewConnectionError('<urllib3.connection.HTTPSConnection object at 0x043EC040>: Failed to establish a new connection: [Errno 11001] getaddrinfo failed')))

or

HTTPSConnectionPool(host='login.microsoftonline.com', port=443): Max retries exceeded with url: /organizations/v2.0/.well-known/openid-configuration (Caused by SSLError(SSLCertVerificationError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1125)'))) az_command_data_logger: HTTPSConnectionPool(host='login.microsoftonline.com', port=443): Max retries exceeded with url: /organizations/v2.0/.well-known/openid-configuration (Caused by SSLError(SSLCertVerificationError(1, '[SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1125)')))
