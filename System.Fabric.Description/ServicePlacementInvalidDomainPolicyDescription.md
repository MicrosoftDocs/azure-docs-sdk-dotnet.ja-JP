<Type Name="ServicePlacementInvalidDomainPolicyDescription" FullName="System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class ServicePlacementInvalidDomainPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePlacementInvalidDomainPolicyDescription extends System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePlacementInvalidDomainPolicyDescription&#xA;Inherits ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementInvalidDomainPolicyDescription = class&#xA;    inherit ServicePlacementPolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServicePlacementPolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="e2eda-101">特定の障害やアップグレード ドメインが必要があります、インスタンスの配置またはにこのポリシーが適用されるサービスのレプリカ用に使用しないことを示すポリシーを表します。</span><span class="sxs-lookup"><span data-stu-id="e2eda-101">Represents a policy which indicates that a particular fault or upgrade domain should not be used for placement of the instances or replicas of the service this policy is applied to.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="e2eda-102">たとえば、地理的に分散リングであるあります可能性があります政治的または法的要件により、特定の地域で実行する必要はありませんが。</span><span class="sxs-lookup"><span data-stu-id="e2eda-102">As an example, in geographically distributed rings there may be a service which must not be run in a particular region due to political or legal requirements.</span></span> <span data-ttu-id="e2eda-103">ここではそのドメインは、このポリシーを無効として定義できます。</span><span class="sxs-lookup"><span data-stu-id="e2eda-103">In this case that domain could be defined as invalid with this policy.</span></span> </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementInvalidDomainPolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e2eda-104"><see cref="T:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e2eda-104">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainName">
      <MemberSignature Language="C#" Value="public string DomainName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.DomainName" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainName As String" />
      <MemberSignature Language="F#" Value="member this.DomainName : string with get, set" Usage="System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.DomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e2eda-105">取得またはそれが無効であるは、このサービスを配置する、文字列として、フォールト ドメインの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="e2eda-105">Gets or sets the name of the fault domain, as a string, that it is invalid to place this service in.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e2eda-106">文字列、それが無効であるは、このサービスを配置すると、フォールト ドメインの名前。</span><span class="sxs-lookup"><span data-stu-id="e2eda-106">The name of the fault domain, as a string, that it is invalid to place this service in.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="servicePlacementInvalidDomainPolicyDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para> 
            <span data-ttu-id="e2eda-107">'InvalidDomain、DomainName' 形式の InvalidDomain サービス配置ポリシーの文字列表現を返す</span><span class="sxs-lookup"><span data-stu-id="e2eda-107">Return a string representation of the InvalidDomain Service Placement Policy in the form 'InvalidDomain, DomainName'</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eda-108">オブジェクトを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="e2eda-108">A string representing the object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>