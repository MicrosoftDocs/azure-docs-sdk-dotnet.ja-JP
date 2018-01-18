<Type Name="ServicePlacementPolicyDescription" FullName="System.Fabric.Description.ServicePlacementPolicyDescription">
  <TypeSignature Language="C#" Value="public abstract class ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServicePlacementPolicyDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementPolicyDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.ServicePlacementRequiredDomainPolicyDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.ServicePlacementNonPartiallyPlaceServicePolicyDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="a125b-101">クラスター内のすべての PlacementPolicyDescription 型の基本データ型を表します。</span><span class="sxs-lookup"><span data-stu-id="a125b-101">Represents the base type for all PlacementPolicyDescription types in the cluster.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServicePlacementPolicyDescription (System.Fabric.Description.ServicePlacementPolicyDescription other);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Description.ServicePlacementPolicyDescription other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementPolicyDescription.#ctor(System.Fabric.Description.ServicePlacementPolicyDescription)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (other As ServicePlacementPolicyDescription)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServicePlacementPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription -&gt; System.Fabric.Description.ServicePlacementPolicyDescription" Usage="new System.Fabric.Description.ServicePlacementPolicyDescription other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Description.ServicePlacementPolicyDescription" />
      </Parameters>
      <Docs>
        <param name="other">
          <para> <span data-ttu-id="a125b-102">新しいオブジェクトを作成する必要があります ServicePlacementPolicyDescription です。</span><span class="sxs-lookup"><span data-stu-id="a125b-102">The ServicePlacementPolicyDescription that the new object should be constructed from.</span></span></para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="a125b-103">A ServicePlacementPolicyDescription のコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="a125b-103">Constructor for a ServicePlacementPolicyDescription</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementPolicyDescription (System.Fabric.Description.ServicePlacementPolicyType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Description.ServicePlacementPolicyType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementPolicyDescription.#ctor(System.Fabric.Description.ServicePlacementPolicyType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As ServicePlacementPolicyType)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServicePlacementPolicyDescription : System.Fabric.Description.ServicePlacementPolicyType -&gt; System.Fabric.Description.ServicePlacementPolicyDescription" Usage="new System.Fabric.Description.ServicePlacementPolicyDescription type" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.Fabric.Description.ServicePlacementPolicyType" />
      </Parameters>
      <Docs>
        <param name="type">
          <para><span data-ttu-id="a125b-104">サービス配置ポリシーの種類。</span><span class="sxs-lookup"><span data-stu-id="a125b-104">The service placement policy type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="a125b-105"><see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a125b-105">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServicePlacementPolicyType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServicePlacementPolicyType Type" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServicePlacementPolicyDescription.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As ServicePlacementPolicyType" />
      <MemberSignature Language="F#" Value="member this.Type : System.Fabric.Description.ServicePlacementPolicyType with get, set" Usage="System.Fabric.Description.ServicePlacementPolicyDescription.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePlacementPolicyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a125b-106">サービス配置ポリシーの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="a125b-106">Gets the service placement policy type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="a125b-107">サービス配置ポリシーの種類。</span><span class="sxs-lookup"><span data-stu-id="a125b-107">The service placement policy type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>