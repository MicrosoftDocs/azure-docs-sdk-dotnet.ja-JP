<Type Name="KeyVaultClient+AuthenticationCallback" FullName="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback">
  <TypeSignature Language="C#" Value="public delegate System.Threading.Tasks.Task&lt;string&gt; KeyVaultClient.AuthenticationCallback(string authority, string resource, string scope);" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed KeyVaultClient/AuthenticationCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function KeyVaultClient.AuthenticationCallback(authority As String, resource As String, scope As String) As Task(Of String) " />
  <TypeSignature Language="F#" Value="type KeyVaultClient.AuthenticationCallback = delegate of string * string * string -&gt; Task&lt;string&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="authority" Type="System.String" />
    <Parameter Name="resource" Type="System.String" />
    <Parameter Name="scope" Type="System.String" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="authority"> URL は機関の識別子です。 </param>
    <param name="resource"> URL で、要求されたトークンの受信者は、ターゲット リソースの識別子。 </param>
    <param name="scope"> 認証要求のスコープです。 </param>
    <summary>
            クライアント コードで実装するのには、認証コールバック デリゲート
            </summary>
    <returns> Twitter アプリケーションの </returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>