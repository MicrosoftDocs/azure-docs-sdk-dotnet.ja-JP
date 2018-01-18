<Type Name="SecurityGroupViewParameters" FullName="Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters">
  <TypeSignature Language="C#" Value="public class SecurityGroupViewParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityGroupViewParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityGroupViewParameters" />
  <TypeSignature Language="F#" Value="type SecurityGroupViewParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="de4c5-101">セキュリティ グループをチェックする VM を定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="de4c5-101">Parameters that define the VM to check security groups for.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupViewParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="de4c5-102">SecurityGroupViewParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de4c5-102">Initializes a new instance of the SecurityGroupViewParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupViewParameters (string targetResourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters : string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters targetResourceId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceId"><span data-ttu-id="de4c5-103">ターゲットの VM の ID です。</span><span class="sxs-lookup"><span data-stu-id="de4c5-103">ID of the target VM.</span></span></param>
        <summary>
            <span data-ttu-id="de4c5-104">SecurityGroupViewParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de4c5-104">Initializes a new instance of the SecurityGroupViewParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de4c5-105">取得またはターゲットの VM の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="de4c5-105">Gets or sets ID of the target VM.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="securityGroupViewParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="de4c5-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="de4c5-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="de4c5-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="de4c5-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>