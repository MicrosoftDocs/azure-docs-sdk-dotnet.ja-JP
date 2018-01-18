<Type Name="UserUpdateParametersInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner">
  <TypeSignature Language="C#" Value="public class UserUpdateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserUpdateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class UserUpdateParametersInner" />
  <TypeSignature Language="F#" Value="type UserUpdateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2db4e-101">既存の職場または学校アカウントのユーザーを更新するためのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="2db4e-101">Request parameters for updating an existing work or school account user.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserUpdateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2db4e-102">UserUpdateParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2db4e-102">Initializes a new instance of the UserUpdateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserUpdateParametersInner (Nullable&lt;bool&gt; accountEnabled = null, string displayName = null, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile passwordProfile = null, string mailNickname = null, string usageLocation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; accountEnabled, string displayName, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile passwordProfile, string mailNickname, string usageLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.#ctor(System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner : Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile * string * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner (accountEnabled, displayName, passwordProfile, mailNickname, usageLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="passwordProfile" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile" />
        <Parameter Name="mailNickname" Type="System.String" />
        <Parameter Name="usageLocation" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountEnabled">To be added.</param>
        <param name="displayName">To be added.</param>
        <param name="passwordProfile">To be added.</param>
        <param name="mailNickname">To be added.</param>
        <param name="usageLocation">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AccountEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AccountEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.AccountEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AccountEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.AccountEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2db4e-103">取得またはアカウントが有効になっているかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="2db4e-103">Gets or sets whether the account is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2db4e-104">取得またはユーザーの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2db4e-104">Gets or sets the display name of the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MailNickname">
      <MemberSignature Language="C#" Value="public string MailNickname { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MailNickname" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.MailNickname" />
      <MemberSignature Language="VB.NET" Value="Public Property MailNickname As String" />
      <MemberSignature Language="F#" Value="member this.MailNickname : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.MailNickname" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mailNickname")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2db4e-105">取得またはユーザーのメールの別名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2db4e-105">Gets or sets the mail alias for the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile PasswordProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile PasswordProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.PasswordProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property PasswordProfile As PasswordProfile" />
      <MemberSignature Language="F#" Value="member this.PasswordProfile : Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.PasswordProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passwordProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2db4e-106">取得またはユーザーのパスワード プロファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="2db4e-106">Gets or sets the password profile of the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageLocation">
      <MemberSignature Language="C#" Value="public string UsageLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UsageLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.UsageLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property UsageLocation As String" />
      <MemberSignature Language="F#" Value="member this.UsageLocation : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.UsageLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usageLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="userUpdateParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2db4e-107">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2db4e-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2db4e-108">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2db4e-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>