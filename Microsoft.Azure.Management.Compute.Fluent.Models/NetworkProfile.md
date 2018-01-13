<Type Name="NetworkProfile" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile">
  <TypeSignature Language="C#" Value="public class NetworkProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkProfile" />
  <TypeSignature Language="F#" Value="type NetworkProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="580cc-101">ネットワーク プロファイルを説明します。</span><span class="sxs-lookup"><span data-stu-id="580cc-101">Describes a network profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="580cc-102">NetworkProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="580cc-102">Initializes a new instance of the NetworkProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkProfile (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.NetworkInterfaceReferenceInner&gt; networkInterfaces = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.NetworkInterfaceReferenceInner&gt; networkInterfaces) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.NetworkInterfaceReferenceInner})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional networkInterfaces As IList(Of NetworkInterfaceReferenceInner) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.NetworkInterfaceReferenceInner&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile networkInterfaces" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="networkInterfaces" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.NetworkInterfaceReferenceInner&gt;" />
      </Parameters>
      <Docs>
        <param name="networkInterfaces"><span data-ttu-id="580cc-103">仮想マシンに関連付けられているネットワーク インターフェイスのリソース Id の一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="580cc-103">Specifies the list of resource IDs for the network interfaces associated with the virtual machine.</span></span></param>
        <summary>
            <span data-ttu-id="580cc-104">NetworkProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="580cc-104">Initializes a new instance of the NetworkProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.NetworkInterfaceReferenceInner&gt; NetworkInterfaces { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.NetworkInterfaceReferenceInner&gt; NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaces As IList(Of NetworkInterfaceReferenceInner)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.NetworkInterfaceReferenceInner&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterfaces")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.NetworkInterfaceReferenceInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="580cc-105">取得または設定は、仮想マシンに関連付けられているネットワーク インターフェイスのリソース Id のリストを指定します。</span><span class="sxs-lookup"><span data-stu-id="580cc-105">Gets or sets specifies the list of resource IDs for the network interfaces associated with the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>