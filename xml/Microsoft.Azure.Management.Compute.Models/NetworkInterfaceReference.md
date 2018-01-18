<Type Name="NetworkInterfaceReference" FullName="Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceReference : Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceReference extends Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceReference&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceReference = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1a98c-101">ネットワーク インターフェイスのリファレンスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="1a98c-101">Describes a network interface reference.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference.#ctor" />
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
            <span data-ttu-id="1a98c-102">NetworkInterfaceReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1a98c-102">Initializes a new instance of the NetworkInterfaceReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceReference (string id = null, Nullable&lt;bool&gt; primary = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype System.Nullable`1&lt;bool&gt; primary) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference.#ctor(System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional primary As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference : string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference" Usage="new Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference (id, primary)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1a98c-103">リソース Id</span><span class="sxs-lookup"><span data-stu-id="1a98c-103">Resource Id</span></span></param>
        <param name="primary"><span data-ttu-id="1a98c-104">バーチャル マシンが 1 つ以上のネットワーク インターフェイスを持つ場合に、プライマリ ネットワーク インターフェイスを指定します。</span><span class="sxs-lookup"><span data-stu-id="1a98c-104">Specifies the primary network interface in case the virtual machine has more than 1 network interface.</span></span></param>
        <summary>
            <span data-ttu-id="1a98c-105">NetworkInterfaceReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1a98c-105">Initializes a new instance of the NetworkInterfaceReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.NetworkInterfaceReference.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a98c-106">取得または設定は、バーチャル マシンが 1 つ以上のネットワーク インターフェイスを持つ場合に、プライマリ ネットワーク インターフェイスを指定します。</span><span class="sxs-lookup"><span data-stu-id="1a98c-106">Gets or sets specifies the primary network interface in case the virtual machine has more than 1 network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>