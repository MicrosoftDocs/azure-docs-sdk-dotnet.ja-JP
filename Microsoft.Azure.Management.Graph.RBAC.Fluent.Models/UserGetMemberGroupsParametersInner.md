<Type Name="UserGetMemberGroupsParametersInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner">
  <TypeSignature Language="C#" Value="public class UserGetMemberGroupsParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserGetMemberGroupsParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class UserGetMemberGroupsParametersInner" />
  <TypeSignature Language="F#" Value="type UserGetMemberGroupsParametersInner = class" />
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
            <span data-ttu-id="c76b1-101">GetMemberGroups API 呼び出しのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c76b1-101">Request parameters for GetMemberGroups API call.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserGetMemberGroupsParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c76b1-102">UserGetMemberGroupsParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c76b1-102">Initializes a new instance of the UserGetMemberGroupsParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserGetMemberGroupsParametersInner (bool securityEnabledOnly);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool securityEnabledOnly) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (securityEnabledOnly As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner : bool -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner securityEnabledOnly" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityEnabledOnly" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="securityEnabledOnly"><span data-ttu-id="c76b1-103">True の場合、セキュリティが有効なグループのメンバーシップのみをチェックする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c76b1-103">If true, only membership in security-enabled groups should be checked.</span></span> <span data-ttu-id="c76b1-104">それ以外の場合、すべてのグループのメンバーシップをチェックする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c76b1-104">Otherwise, membership in all groups should be checked.</span></span></param>
        <summary>
            <span data-ttu-id="c76b1-105">UserGetMemberGroupsParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c76b1-105">Initializes a new instance of the UserGetMemberGroupsParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityEnabledOnly">
      <MemberSignature Language="C#" Value="public bool SecurityEnabledOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SecurityEnabledOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner.SecurityEnabledOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityEnabledOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.SecurityEnabledOnly : bool with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner.SecurityEnabledOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="securityEnabledOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c76b1-106">取得または設定 true の場合、セキュリティが有効なグループのメンバーシップのみをチェックする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c76b1-106">Gets or sets if true, only membership in security-enabled groups should be checked.</span></span> <span data-ttu-id="c76b1-107">それ以外の場合、すべてのグループのメンバーシップをチェックする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c76b1-107">Otherwise, membership in all groups should be checked.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="userGetMemberGroupsParametersInner.Validate " />
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
            <span data-ttu-id="c76b1-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c76b1-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c76b1-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c76b1-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>