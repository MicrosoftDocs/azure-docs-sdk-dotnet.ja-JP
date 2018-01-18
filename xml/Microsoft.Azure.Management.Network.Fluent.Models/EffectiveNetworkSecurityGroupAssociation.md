<Type Name="EffectiveNetworkSecurityGroupAssociation" FullName="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation">
  <TypeSignature Language="C#" Value="public class EffectiveNetworkSecurityGroupAssociation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveNetworkSecurityGroupAssociation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveNetworkSecurityGroupAssociation" />
  <TypeSignature Language="F#" Value="type EffectiveNetworkSecurityGroupAssociation = class" />
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
            <span data-ttu-id="aa0e9-101">有効なネットワーク セキュリティ グループの関連付け。</span><span class="sxs-lookup"><span data-stu-id="aa0e9-101">The effective network security group association.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityGroupAssociation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aa0e9-102">EffectiveNetworkSecurityGroupAssociation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="aa0e9-102">Initializes a new instance of the EffectiveNetworkSecurityGroupAssociation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityGroupAssociation (Microsoft.Azure.Management.ResourceManager.Fluent.SubResource subnet = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource networkInterface = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource subnet, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource networkInterface) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation.#ctor(Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional subnet As SubResource = null, Optional networkInterface As SubResource = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource -&gt; Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation (subnet, networkInterface)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="networkInterface" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
      </Parameters>
      <Docs>
        <param name="subnet"><span data-ttu-id="aa0e9-103">割り当てられている場合、サブネットの ID。</span><span class="sxs-lookup"><span data-stu-id="aa0e9-103">The ID of the subnet if assigned.</span></span></param>
        <param name="networkInterface"><span data-ttu-id="aa0e9-104">割り当てられている場合、ネットワーク インターフェイスの ID です。</span><span class="sxs-lookup"><span data-stu-id="aa0e9-104">The ID of the network interface if assigned.</span></span></param>
        <summary>
            <span data-ttu-id="aa0e9-105">EffectiveNetworkSecurityGroupAssociation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="aa0e9-105">Initializes a new instance of the EffectiveNetworkSecurityGroupAssociation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource NetworkInterface { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource NetworkInterface" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation.NetworkInterface" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterface As SubResource" />
      <MemberSignature Language="F#" Value="member this.NetworkInterface : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation.NetworkInterface" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterface")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa0e9-106">取得または割り当てられている場合に、ネットワーク インターフェイスの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="aa0e9-106">Gets or sets the ID of the network interface if assigned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As SubResource" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupAssociation.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa0e9-107">取得または割り当てられている場合に、サブネットの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="aa0e9-107">Gets or sets the ID of the subnet if assigned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>