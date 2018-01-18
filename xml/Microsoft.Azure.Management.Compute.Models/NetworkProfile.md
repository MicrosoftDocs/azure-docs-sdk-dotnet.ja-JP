<Type Name="NetworkProfile" FullName="Microsoft.Azure.Management.Compute.Models.NetworkProfile">
  <TypeSignature Language="C#" Value="public class NetworkProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.NetworkProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkProfile" />
  <TypeSignature Language="F#" Value="type NetworkProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b093-101">仮想マシンのネットワーク インターフェイスを指定します。</span><span class="sxs-lookup"><span data-stu-id="1b093-101">Specifies the network interfaces of the virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.NetworkProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b093-102">NetworkProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b093-102">Initializes a new instance of the NetworkProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkProfile (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference&gt; networkInterfaces = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference&gt; networkInterfaces) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.NetworkProfile.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional networkInterfaces As IList(Of NetworkInterfaceReference) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.NetworkProfile : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference&gt; -&gt; Microsoft.Azure.Management.Compute.Models.NetworkProfile" Usage="new Microsoft.Azure.Management.Compute.Models.NetworkProfile networkInterfaces" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="networkInterfaces" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference&gt;" />
      </Parameters>
      <Docs>
        <param name="networkInterfaces"><span data-ttu-id="1b093-103">仮想マシンに関連付けられているネットワーク インターフェイスのリソース Id の一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="1b093-103">Specifies the list of resource Ids for the network interfaces associated with the virtual machine.</span></span></param>
        <summary>
            <span data-ttu-id="1b093-104">NetworkProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b093-104">Initializes a new instance of the NetworkProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference&gt; NetworkInterfaces { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference&gt; NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.NetworkProfile.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaces As IList(Of NetworkInterfaceReference)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.NetworkProfile.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterfaces")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b093-105">取得または設定は、仮想マシンに関連付けられているネットワーク インターフェイスのリソース Id のリストを指定します。</span><span class="sxs-lookup"><span data-stu-id="1b093-105">Gets or sets specifies the list of resource Ids for the network interfaces associated with the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>