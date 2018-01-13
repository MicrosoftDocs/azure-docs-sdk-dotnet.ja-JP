<Type Name="UserAccountSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings">
  <TypeSignature Language="C#" Value="public class UserAccountSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserAccountSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class UserAccountSettings" />
  <TypeSignature Language="F#" Value="type UserAccountSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            各クラスターのノード上で作成されるユーザー アカウントの設定です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccountSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            UserAccountSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccountSettings (string adminUserName, string adminUserSshPublicKey = null, string adminUserPassword = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string adminUserName, string adminUserSshPublicKey, string adminUserPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (adminUserName As String, Optional adminUserSshPublicKey As String = null, Optional adminUserPassword As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings : string * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings (adminUserName, adminUserSshPublicKey, adminUserPassword)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="adminUserName" Type="System.String" />
        <Parameter Name="adminUserSshPublicKey" Type="System.String" />
        <Parameter Name="adminUserPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminUserName">管理者アカウントの名前を指定します。</param>
        <param name="adminUserSshPublicKey">Vm を linux での認証に使用する SSH 公開キーに基づいています。 これは、返されない GET 応答本文にします。</param>
        <param name="adminUserPassword">管理者のユーザー パスワード (linux の場合のみ)。
            これは、返されない GET 応答本文にします。</param>
        <summary>
            UserAccountSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserName">
      <MemberSignature Language="C#" Value="public string AdminUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserName As String" />
      <MemberSignature Language="F#" Value="member this.AdminUserName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、管理者アカウントの名前を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserPassword">
      <MemberSignature Language="C#" Value="public string AdminUserPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUserPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdminUserPassword : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUserPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の管理ユーザーのパスワード (linux の場合のみ)。 これは、返されない GET 応答本文にします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserSshPublicKey">
      <MemberSignature Language="C#" Value="public string AdminUserSshPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUserSshPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserSshPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserSshPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.AdminUserSshPublicKey : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserSshPublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUserSshPublicKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または linux ベースの Vm での認証に使用する SSH 公開キーを設定します。 これは、返されない GET 応答本文にします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="userAccountSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>