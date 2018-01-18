<Type Name="DiskInstanceView" FullName="Microsoft.Azure.Management.Compute.Models.DiskInstanceView">
  <TypeSignature Language="C#" Value="public class DiskInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiskInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.DiskInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class DiskInstanceView" />
  <TypeSignature Language="F#" Value="type DiskInstanceView = class" />
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
            <span data-ttu-id="be28d-101">ディスクのインスタンス ビューです。</span><span class="sxs-lookup"><span data-stu-id="be28d-101">The instance view of the disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiskInstanceView.#ctor" />
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
            <span data-ttu-id="be28d-102">DiskInstanceView クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="be28d-102">Initializes a new instance of the DiskInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskInstanceView (string name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings&gt; encryptionSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings&gt; encryptionSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiskInstanceView.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.InstanceViewStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional encryptionSettings As IList(Of DiskEncryptionSettings) = null, Optional statuses As IList(Of InstanceViewStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.DiskInstanceView : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; -&gt; Microsoft.Azure.Management.Compute.Models.DiskInstanceView" Usage="new Microsoft.Azure.Management.Compute.Models.DiskInstanceView (name, encryptionSettings, statuses)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="encryptionSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings&gt;" />
        <Parameter Name="statuses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="be28d-103">ディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="be28d-103">The disk name.</span></span></param>
        <param name="encryptionSettings"><span data-ttu-id="be28d-104">OS ディスクの暗号化の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="be28d-104">Specifies the encryption settings for the OS Disk.</span></span> <span data-ttu-id="be28d-105">&lt;ブラジル&gt;&lt;br&gt;最小 api バージョン: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="be28d-105">&lt;br&gt;&lt;br&gt; Minimum api-version: 2015-06-15</span></span></param>
        <param name="statuses"><span data-ttu-id="be28d-106">リソースの状態情報です。</span><span class="sxs-lookup"><span data-stu-id="be28d-106">The resource status information.</span></span></param>
        <summary>
            <span data-ttu-id="be28d-107">DiskInstanceView クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="be28d-107">Initializes a new instance of the DiskInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings&gt; EncryptionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings&gt; EncryptionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiskInstanceView.EncryptionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionSettings As IList(Of DiskEncryptionSettings)" />
      <MemberSignature Language="F#" Value="member this.EncryptionSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.DiskInstanceView.EncryptionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be28d-108">取得または設定は、OS ディスクの暗号化の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="be28d-108">Gets or sets specifies the encryption settings for the OS Disk.</span></span>
            <span data-ttu-id="be28d-109">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;最小 api バージョン: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="be28d-109">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Minimum api-version: 2015-06-15</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiskInstanceView.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.DiskInstanceView.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="be28d-110">取得またはディスクの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="be28d-110">Gets or sets the disk name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiskInstanceView.Statuses" />
      <MemberSignature Language="VB.NET" Value="Public Property Statuses As IList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Statuses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.DiskInstanceView.Statuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statuses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be28d-111">取得またはリソースの状態情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="be28d-111">Gets or sets the resource status information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>