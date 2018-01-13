<Type Name="UserInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.UserInner">
  <TypeSignature Language="C#" Value="public class UserInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.UserInner" />
  <TypeSignature Language="VB.NET" Value="Public Class UserInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type UserInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b59bc-101">アクティビティのパブリッシュに使用されるユーザー crendentials です。</span><span class="sxs-lookup"><span data-stu-id="b59bc-101">User crendentials used for publishing activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b59bc-102">UserInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b59bc-102">Initializes a new instance of the UserInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserInner (string id = null, string name = null, string kind = null, string type = null, string userName = null, string publishingUserName = null, string publishingPassword = null, string publishingPasswordHash = null, string publishingPasswordHashSalt = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string userName, string publishingUserName, string publishingPassword, string publishingPasswordHash, string publishingPasswordHashSalt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional userName As String = null, Optional publishingUserName As String = null, Optional publishingPassword As String = null, Optional publishingPasswordHash As String = null, Optional publishingPasswordHashSalt As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.UserInner : string * string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.UserInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.UserInner (id, name, kind, type, userName, publishingUserName, publishingPassword, publishingPasswordHash, publishingPasswordHashSalt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="userName">To be added.</param>
        <param name="publishingUserName">To be added.</param>
        <param name="publishingPassword">To be added.</param>
        <param name="publishingPasswordHash">To be added.</param>
        <param name="publishingPasswordHashSalt">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingPassword">
      <MemberSignature Language="C#" Value="public string PublishingPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.PublishingPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingPassword As String" />
      <MemberSignature Language="F#" Value="member this.PublishingPassword : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.PublishingPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="b59bc-103">取得または発行に使用されるパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="b59bc-103">Gets or sets password used for publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingPasswordHash">
      <MemberSignature Language="C#" Value="public string PublishingPasswordHash { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingPasswordHash" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.PublishingPasswordHash" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingPasswordHash As String" />
      <MemberSignature Language="F#" Value="member this.PublishingPasswordHash : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.PublishingPasswordHash" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="b59bc-104">取得または発行に使用されるパスワード ハッシュを設定します。</span><span class="sxs-lookup"><span data-stu-id="b59bc-104">Gets or sets password hash used for publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingPasswordHashSalt">
      <MemberSignature Language="C#" Value="public string PublishingPasswordHashSalt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingPasswordHashSalt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.PublishingPasswordHashSalt" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingPasswordHashSalt As String" />
      <MemberSignature Language="F#" Value="member this.PublishingPasswordHashSalt : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.PublishingPasswordHashSalt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="b59bc-105">取得または発行に使用されるパスワードのハッシュ ソルトを設定します。</span><span class="sxs-lookup"><span data-stu-id="b59bc-105">Gets or sets password hash salt used for publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingUserName">
      <MemberSignature Language="C#" Value="public string PublishingUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.PublishingUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingUserName As String" />
      <MemberSignature Language="F#" Value="member this.PublishingUserName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.PublishingUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="b59bc-106">取得または発行に使用されるユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b59bc-106">Gets or sets username used for publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.UserInner.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="b59bc-107">取得またはユーザー名を設定</span><span class="sxs-lookup"><span data-stu-id="b59bc-107">Gets or sets username</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>