<Type Name="HttpLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService">
  <TypeSignature Language="C#" Value="public class HttpLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type HttpLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("Http")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            HTTP エンドポイントにリンクされたサービス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpLinkedService (string url, string authenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, string authenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, authenticationType As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService (url, authenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService" />必須の引数を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 HTTP サーバーへの接続に使用する認証の種類。
            いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.HttpAuthenticationType" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertThumbprint">
      <MemberSignature Language="C#" Value="public string CertThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.CertThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property CertThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.CertThumbprint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.CertThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 ClientCertificate 認証用の証明書の拇印です。 内部設置型のコピーに対してのみ有効です。
            ClientCertificate 認証では、内部設置型のコピー、CertThumbprint または EmbeddedCertData/パスワードのいずれかを指定する必要があります。
            
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmbeddedCertData">
      <MemberSignature Language="C#" Value="public string EmbeddedCertData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmbeddedCertData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EmbeddedCertData" />
      <MemberSignature Language="VB.NET" Value="Public Property EmbeddedCertData As String" />
      <MemberSignature Language="F#" Value="member this.EmbeddedCertData : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EmbeddedCertData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 ClientCertificate 認証用の証明書データを Base64 にエンコードされます。 ClientCertificate 認証では、内部設置型のコピー、CertThumbprint または EmbeddedCertData/パスワードのいずれかを指定する必要があります。
            
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableServerCertificateValidation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableServerCertificateValidation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableServerCertificateValidation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EnableServerCertificateValidation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableServerCertificateValidation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableServerCertificateValidation : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EnableServerCertificateValidation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 True の場合、HTTP サーバーの SSL 証明書の検証と SSL や TLS チャネル経由で接続します。
            既定値は true です。
            このプロパティを検証をスキップする場合は false に設定することは推奨されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public string EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As String" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 基本認証、ダイジェスト、Windows または ClientCertificate 認証、内部設置型のコピーに対してのみ有効に暗号化された資格情報です。
            非匿名認証でのコピーを内部設置型、ユーザー名/パスワード、ClientThumbprint、EmbeddedCertData/パスワードまたは EncryptedCredential を指定してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.GatewayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 オンプレミス ゲートウェイの名前です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 EmbeddedCertData 認証と基本認証、ダイジェスト、Windows、または ClientCertificate のパスワードです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 例: http://www.microsoft.com、HTTP エンドポイントのベース URL。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HttpLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 基本認証、ダイジェスト認証、または Windows 認証のユーザー名。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>