<Type Name="PoolStopResizeHeaders" FullName="Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders">
  <TypeSignature Language="C#" Value="public class PoolStopResizeHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolStopResizeHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolStopResizeHeaders" />
  <TypeSignature Language="F#" Value="type PoolStopResizeHeaders = class" />
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
            <span data-ttu-id="6b093-101">StopResize 操作のヘッダーを定義します。</span><span class="sxs-lookup"><span data-stu-id="6b093-101">Defines headers for StopResize operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolStopResizeHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6b093-102">PoolStopResizeHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b093-102">Initializes a new instance of the PoolStopResizeHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolStopResizeHeaders (string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders : string -&gt; Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders" Usage="new Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders eTag" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag"><span data-ttu-id="6b093-103">ETag HTTP 応答ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="6b093-103">The ETag HTTP response header.</span></span> <span data-ttu-id="6b093-104">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="6b093-104">This is an opaque string.</span></span> <span data-ttu-id="6b093-105">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="6b093-105">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="6b093-106">具体的には、If-match または [なし]-If-match ヘッダーのいずれかに ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="6b093-106">In particular, you can pass the ETag to one of the If-Match or If-None-Match headers.</span></span></param>
        <summary>
            <span data-ttu-id="6b093-107">PoolStopResizeHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b093-107">Initializes a new instance of the PoolStopResizeHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b093-108">取得または ETag HTTP 応答ヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="6b093-108">Gets or sets the ETag HTTP response header.</span></span> <span data-ttu-id="6b093-109">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="6b093-109">This is an opaque string.</span></span> <span data-ttu-id="6b093-110">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="6b093-110">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="6b093-111">具体的には、If-match または [なし]-If-match ヘッダーのいずれかに ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="6b093-111">In particular, you can pass the ETag to one of the If-Match or If-None-Match headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>