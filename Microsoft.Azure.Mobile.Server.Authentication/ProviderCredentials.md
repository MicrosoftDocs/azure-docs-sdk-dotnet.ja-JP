<Type Name="ProviderCredentials" FullName="Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials">
  <TypeSignature Language="C#" Value="public abstract class ProviderCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ProviderCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ProviderCredentials" />
  <TypeSignature Language="F#" Value="type ProviderCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            すべてのプロバイダーの特定資格情報の基本クラス。 プロバイダー固有のサブクラスは、特定の情報を追加、たとえばトークン、トークン シークレットなどにアクセスします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ProviderCredentials (string providerName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string providerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (providerName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials : string -&gt; Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" Usage="new Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials providerName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="providerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="providerName">プロバイダーの名前。</param>
        <summary>
            このインスタンスに関連付けられているプロバイダーの名前の新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、これらの資格情報プロバイダーの名前。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserClaims">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;System.Security.Claims.Claim&gt; UserClaims { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Security.Claims.Claim&gt; UserClaims" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.UserClaims" />
      <MemberSignature Language="VB.NET" Value="Public Property UserClaims As IEnumerable(Of Claim)" />
      <MemberSignature Language="F#" Value="member this.UserClaims : seq&lt;System.Security.Claims.Claim&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.UserClaims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Security.Claims.Claim&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのインスタンスに関連付けられているその他のクレームのコレクションを設定します。 Null または空にすることがあります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public string UserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Property UserId As String" />
      <MemberSignature Language="F#" Value="member this.UserId : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.UserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザーのプロバイダー id を設定します。 値が作成できるおよびによって提供されるメソッドを使用して解析<see cref="T:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>