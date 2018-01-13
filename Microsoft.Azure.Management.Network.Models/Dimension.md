<Type Name="Dimension" FullName="Microsoft.Azure.Management.Network.Models.Dimension">
  <TypeSignature Language="C#" Value="public class Dimension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Dimension extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.Dimension" />
  <TypeSignature Language="VB.NET" Value="Public Class Dimension" />
  <TypeSignature Language="F#" Value="type Dimension = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f9aad-101">メトリックのディメンションです。</span><span class="sxs-lookup"><span data-stu-id="f9aad-101">Dimension of the metric.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Dimension ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Dimension.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f9aad-102">ディメンションのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f9aad-102">Initializes a new instance of the Dimension class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Dimension (string name = null, string displayName = null, string internalName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string internalName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Dimension.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional internalName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.Dimension : string * string * string -&gt; Microsoft.Azure.Management.Network.Models.Dimension" Usage="new Microsoft.Azure.Management.Network.Models.Dimension (name, displayName, internalName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="internalName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f9aad-103">ディメンションの名前。</span><span class="sxs-lookup"><span data-stu-id="f9aad-103">The name of the dimension.</span></span></param>
        <param name="displayName"><span data-ttu-id="f9aad-104">ディメンションの表示名。</span><span class="sxs-lookup"><span data-stu-id="f9aad-104">The display name of the dimension.</span></span></param>
        <param name="internalName"><span data-ttu-id="f9aad-105">ディメンションの内部名。</span><span class="sxs-lookup"><span data-stu-id="f9aad-105">The internal name of the dimension.</span></span></param>
        <summary>
            <span data-ttu-id="f9aad-106">ディメンションのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f9aad-106">Initializes a new instance of the Dimension class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Dimension.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Dimension.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9aad-107">取得またはディメンションの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="f9aad-107">Gets or sets the display name of the dimension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalName">
      <MemberSignature Language="C#" Value="public string InternalName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Dimension.InternalName" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalName As String" />
      <MemberSignature Language="F#" Value="member this.InternalName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Dimension.InternalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9aad-108">取得またはディメンションの内部名を設定します。</span><span class="sxs-lookup"><span data-stu-id="f9aad-108">Gets or sets the internal name of the dimension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Dimension.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Dimension.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9aad-109">取得またはディメンションの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f9aad-109">Gets or sets the name of the dimension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>