<Type Name="User" FullName="Microsoft.Azure.Management.WebSites.Models.User">
  <TypeSignature Language="C#" Value="public class User : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit User extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.User" />
  <TypeSignature Language="VB.NET" Value="Public Class User&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type User = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            アクティビティのパブリッシュに使用されるユーザー crendentials です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public User ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.User.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ユーザー クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public User (string id = null, string name = null, string kind = null, string type = null, string userName = null, string publishingUserName = null, string publishingPassword = null, string publishingPasswordHash = null, string publishingPasswordHashSalt = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string userName, string publishingUserName, string publishingPassword, string publishingPasswordHash, string publishingPasswordHashSalt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.User.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional userName As String = null, Optional publishingUserName As String = null, Optional publishingPassword As String = null, Optional publishingPasswordHash As String = null, Optional publishingPasswordHashSalt As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.User : string * string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.User" Usage="new Microsoft.Azure.Management.WebSites.Models.User (id, name, kind, type, userName, publishingUserName, publishingPassword, publishingPasswordHash, publishingPasswordHashSalt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="publishingUserName" Type="System.String" />
        <Parameter Name="publishingPassword" Type="System.String" />
        <Parameter Name="publishingPasswordHash" Type="System.String" />
        <Parameter Name="publishingPasswordHashSalt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="userName">ユーザー名</param>
        <param name="publishingUserName">発行に使用されるユーザー名。</param>
        <param name="publishingPassword">発行に使用されるパスワードです。</param>
        <param name="publishingPasswordHash">発行に使用されるパスワード ハッシュ。</param>
        <param name="publishingPasswordHashSalt">パスワードのハッシュ ソルト パブリッシュに使用します。</param>
        <summary>
            ユーザー クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingPassword">
      <MemberSignature Language="C#" Value="public string PublishingPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.PublishingPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingPassword As String" />
      <MemberSignature Language="F#" Value="member this.PublishingPassword : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.PublishingPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または発行に使用されるパスワードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingPasswordHash">
      <MemberSignature Language="C#" Value="public string PublishingPasswordHash { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingPasswordHash" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.PublishingPasswordHash" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingPasswordHash As String" />
      <MemberSignature Language="F#" Value="member this.PublishingPasswordHash : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.PublishingPasswordHash" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingPasswordHash")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または発行に使用されるパスワード ハッシュを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingPasswordHashSalt">
      <MemberSignature Language="C#" Value="public string PublishingPasswordHashSalt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingPasswordHashSalt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.PublishingPasswordHashSalt" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingPasswordHashSalt As String" />
      <MemberSignature Language="F#" Value="member this.PublishingPasswordHashSalt : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.PublishingPasswordHashSalt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingPasswordHashSalt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または発行に使用されるパスワードのハッシュ ソルトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingUserName">
      <MemberSignature Language="C#" Value="public string PublishingUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.PublishingUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingUserName As String" />
      <MemberSignature Language="F#" Value="member this.PublishingUserName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.PublishingUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または発行に使用されるユーザー名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.User.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.User.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー名を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>