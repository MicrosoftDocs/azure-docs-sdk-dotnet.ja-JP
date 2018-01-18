<Type Name="ServicePlacementRequiredDomainPolicyDescription" FullName="System.Fabric.Description.ServicePlacementRequiredDomainPolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class ServicePlacementRequiredDomainPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePlacementRequiredDomainPolicyDescription extends System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementRequiredDomainPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePlacementRequiredDomainPolicyDescription&#xA;Inherits ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementRequiredDomainPolicyDescription = class&#xA;    inherit ServicePlacementPolicyDescription" />
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
      <para>
            <span data-ttu-id="3b76c-101">特定のドメインに配置するレプリカを必要とする配置ポリシーの説明。</span><span class="sxs-lookup"><span data-stu-id="3b76c-101">Placement policy description that requires a replica to be placed in a particular domain.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementRequiredDomainPolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementRequiredDomainPolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="3b76c-102">新しい <see cref="T:System.Fabric.Description.ServicePlacementRequiredDomainPolicyDescription" /> オブジェクトをインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="3b76c-102">Instantiates a new <see cref="T:System.Fabric.Description.ServicePlacementRequiredDomainPolicyDescription" /> object.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainName">
      <MemberSignature Language="C#" Value="public string DomainName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServicePlacementRequiredDomainPolicyDescription.DomainName" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainName As String" />
      <MemberSignature Language="F#" Value="member this.DomainName : string with get, set" Usage="System.Fabric.Description.ServicePlacementRequiredDomainPolicyDescription.DomainName" />
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
          <para> 
            <span data-ttu-id="3b76c-103">取得または設定、ServicePlacementRequiredDomainPolicyDescription で指定されたドメインの名前</span><span class="sxs-lookup"><span data-stu-id="3b76c-103">Gets or sets the name of the domain specified in a ServicePlacementRequiredDomainPolicyDescription</span></span>
            </para>
        </summary>
        <value>
          <para> <span data-ttu-id="3b76c-104">ServicePlacementRequiredDomainPolicyDescription が遵守する必要があるドメインの名前を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="3b76c-104">A string containing the name of the domain that the ServicePlacementRequiredDomainPolicyDescription should respect.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementRequiredDomainPolicyDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="servicePlacementRequiredDomainPolicyDescription.ToString " />
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
            <span data-ttu-id="3b76c-105">'RequiredDomain、DomainName' 形式の RequiredDomain サービス配置ポリシーの文字列表現を返す</span><span class="sxs-lookup"><span data-stu-id="3b76c-105">Return a string representation of the RequiredDomain Service Placement Policy in the form 'RequiredDomain, DomainName'</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="3b76c-106">オブジェクトを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="3b76c-106">A string representing the object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>