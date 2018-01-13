<Type Name="AuthenticationParameters" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters">
  <TypeSignature Language="C#" Value="public sealed class AuthenticationParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AuthenticationParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AuthenticationParameters" />
  <TypeSignature Language="F#" Value="type AuthenticationParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            リソース サーバーからの応答を不正に基づく認証パラメーターが含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.Authority" />
      <MemberSignature Language="VB.NET" Value="Public Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークンの発行する機関のアドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromResourceUrlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt; CreateFromResourceUrlAsync (Uri resourceUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt; CreateFromResourceUrlAsync(class System.Uri resourceUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromResourceUrlAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromResourceUrlAsync (resourceUrl As Uri) As Task(Of AuthenticationParameters)" />
      <MemberSignature Language="F#" Value="static member CreateFromResourceUrlAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt;" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromResourceUrlAsync resourceUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters/&lt;CreateFromResourceUrlAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUrl" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="resourceUrl">リソースのアドレス</param>
        <summary>
            リソースのアドレスからの認証パラメーターを作成します。 このメソッドには、権限のない Www-authenticate ヘッダーの認証パラメーターを含む応答を返すリソース サーバーが必要です。
            </summary>
        <returns>認証パラメーターを含む AuthenticationParameters オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromResponseAuthenticateHeader">
      <MemberSignature Language="C#" Value="public static Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters CreateFromResponseAuthenticateHeader (string authenticateHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters CreateFromResponseAuthenticateHeader(string authenticateHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromResponseAuthenticateHeader(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromResponseAuthenticateHeader (authenticateHeader As String) As AuthenticationParameters" />
      <MemberSignature Language="F#" Value="static member CreateFromResponseAuthenticateHeader : string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromResponseAuthenticateHeader authenticateHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authenticateHeader" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authenticateHeader">Www-authenticate ヘッダー ヘッダーの内容</param>
        <summary>
            リソースから受信した応答で Www-authenticate ヘッダーからの認証パラメーターを作成します。 このメソッドには、認証パラメーターを格納するヘッダーが必要です。
            </summary>
        <returns>認証パラメーターを含む AuthenticationParameters オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromUnauthorizedResponseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt; CreateFromUnauthorizedResponseAsync (System.Net.Http.HttpResponseMessage responseMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt; CreateFromUnauthorizedResponseAsync(class System.Net.Http.HttpResponseMessage responseMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromUnauthorizedResponseAsync(System.Net.Http.HttpResponseMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromUnauthorizedResponseAsync (responseMessage As HttpResponseMessage) As Task(Of AuthenticationParameters)" />
      <MemberSignature Language="F#" Value="static member CreateFromUnauthorizedResponseAsync : System.Net.Http.HttpResponseMessage -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt;" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.CreateFromUnauthorizedResponseAsync responseMessage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters/&lt;CreateFromUnauthorizedResponseAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="responseMessage" Type="System.Net.Http.HttpResponseMessage" />
      </Parameters>
      <Docs>
        <param name="responseMessage">(例: HttpClient を使用して http 呼び出し) 経由でリソースから受信した応答します。</param>
        <summary>
            リソースから受け取った応答から受信した応答からの認証パラメーターを作成します。 このメソッドは、状態および認証パラメーターを含む Www-authenticate ヘッダーが許可されていないへの応答を期待しています。</summary>
        <returns>認証パラメーターを含む AuthenticationParameters オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.Resource" />
      <MemberSignature Language="VB.NET" Value="Public Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationParameters.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求されたトークンの受信者は、ターゲット リソースの識別子を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>