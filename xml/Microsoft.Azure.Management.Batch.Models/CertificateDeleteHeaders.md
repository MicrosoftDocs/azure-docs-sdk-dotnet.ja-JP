<Type Name="CertificateDeleteHeaders" FullName="Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders">
  <TypeSignature Language="C#" Value="public class CertificateDeleteHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateDeleteHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateDeleteHeaders" />
  <TypeSignature Language="F#" Value="type CertificateDeleteHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8445b-101">削除操作のヘッダーを定義します。</span><span class="sxs-lookup"><span data-stu-id="8445b-101">Defines headers for Delete operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateDeleteHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8445b-102">CertificateDeleteHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8445b-102">Initializes a new instance of the CertificateDeleteHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateDeleteHeaders (string location = null, Nullable&lt;int&gt; retryAfter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, valuetype System.Nullable`1&lt;int32&gt; retryAfter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional retryAfter As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" Usage="new Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders (location, retryAfter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="retryAfter" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="8445b-103">非同期操作の状態を確認するために使用されたリソースの URL です。</span><span class="sxs-lookup"><span data-stu-id="8445b-103">The URL of the resource used to check the status of the asynchronous operation.</span></span></param>
        <param name="retryAfter"><span data-ttu-id="8445b-104">非同期操作の状態を確認するための推奨されています。</span><span class="sxs-lookup"><span data-stu-id="8445b-104">Suggested delay to check the status of the asynchronous operation.</span></span> <span data-ttu-id="8445b-105">値は、秒を表す整数です。</span><span class="sxs-lookup"><span data-stu-id="8445b-105">The value is an integer that represents the seconds.</span></span></param>
        <summary>
            <span data-ttu-id="8445b-106">CertificateDeleteHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8445b-106">Initializes a new instance of the CertificateDeleteHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8445b-107">取得または非同期操作の状態を確認するために使用されたリソースの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="8445b-107">Gets or sets the URL of the resource used to check the status of the asynchronous operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryAfter">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetryAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetryAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders.RetryAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryAfter As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetryAfter : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders.RetryAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Retry-After")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8445b-108">取得または非同期操作の状態を確認する推奨の遅延を設定します。</span><span class="sxs-lookup"><span data-stu-id="8445b-108">Gets or sets suggested delay to check the status of the asynchronous operation.</span></span> <span data-ttu-id="8445b-109">値は、秒を表す整数です。</span><span class="sxs-lookup"><span data-stu-id="8445b-109">The value is an integer that represents the seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>