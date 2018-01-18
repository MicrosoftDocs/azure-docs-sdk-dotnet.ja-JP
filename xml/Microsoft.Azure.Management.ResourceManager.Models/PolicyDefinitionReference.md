<Type Name="PolicyDefinitionReference" FullName="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference">
  <TypeSignature Language="C#" Value="public class PolicyDefinitionReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolicyDefinitionReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference" />
  <TypeSignature Language="VB.NET" Value="Public Class PolicyDefinitionReference" />
  <TypeSignature Language="F#" Value="type PolicyDefinitionReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="97193-101">ポリシー定義の参照。</span><span class="sxs-lookup"><span data-stu-id="97193-101">The policy definition reference.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicyDefinitionReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="97193-102">PolicyDefinitionReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="97193-102">Initializes a new instance of the PolicyDefinitionReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicyDefinitionReference (string policyDefinitionId = null, object parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string policyDefinitionId, object parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference.#ctor(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional policyDefinitionId As String = null, Optional parameters As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference : string * obj -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference" Usage="new Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference (policyDefinitionId, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="policyDefinitionId" Type="System.String" />
        <Parameter Name="parameters" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="policyDefinitionId"><span data-ttu-id="97193-103">ポリシー定義またはポリシーの ID は、定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="97193-103">The ID of the policy definition or policy set definition.</span></span></param>
        <param name="parameters"><span data-ttu-id="97193-104">ポリシーのルールでパラメーターを使用するかどうかに必要です。</span><span class="sxs-lookup"><span data-stu-id="97193-104">Required if a parameter is used in policy rule.</span></span></param>
        <summary>
            <span data-ttu-id="97193-105">PolicyDefinitionReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="97193-105">Initializes a new instance of the PolicyDefinitionReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public object Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As Object" />
      <MemberSignature Language="F#" Value="member this.Parameters : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97193-106">取得または設定ポリシーのルールのパラメーターを使用する場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="97193-106">Gets or sets required if a parameter is used in policy rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyDefinitionId">
      <MemberSignature Language="C#" Value="public string PolicyDefinitionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyDefinitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference.PolicyDefinitionId" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyDefinitionId As String" />
      <MemberSignature Language="F#" Value="member this.PolicyDefinitionId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinitionReference.PolicyDefinitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyDefinitionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97193-107">取得またはポリシーの定義またはポリシーのセットの定義の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="97193-107">Gets or sets the ID of the policy definition or policy set definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>