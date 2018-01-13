<Type Name="BlobSink" FullName="Microsoft.Azure.Management.DataFactories.Models.BlobSink">
  <TypeSignature Language="C#" Value="public class BlobSink : Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobSink extends Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.BlobSink" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type BlobSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3be39-101">コピー アクティビティ blob シンクです。</span><span class="sxs-lookup"><span data-stu-id="3be39-101">A copy activity blob sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.BlobSink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSink (int writeBatchSize, TimeSpan writeBatchTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 writeBatchSize, valuetype System.TimeSpan writeBatchTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.BlobSink.#ctor(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (writeBatchSize As Integer, writeBatchTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.BlobSink : int * TimeSpan -&gt; Microsoft.Azure.Management.DataFactories.Models.BlobSink" Usage="new Microsoft.Azure.Management.DataFactories.Models.BlobSink (writeBatchSize, writeBatchTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="writeBatchSize" Type="System.Int32" />
        <Parameter Name="writeBatchTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="writeBatchSize">To be added.</param>
        <param name="writeBatchTimeout">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobWriterAddHeader">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; BlobWriterAddHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; BlobWriterAddHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.BlobSink.BlobWriterAddHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobWriterAddHeader As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.BlobWriterAddHeader : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.BlobSink.BlobWriterAddHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3be39-102">Blob のライターでは、ヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="3be39-102">Blob writer add header.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobWriterDateTimeFormat">
      <MemberSignature Language="C#" Value="public string BlobWriterDateTimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobWriterDateTimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.BlobSink.BlobWriterDateTimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobWriterDateTimeFormat As String" />
      <MemberSignature Language="F#" Value="member this.BlobWriterDateTimeFormat : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.BlobSink.BlobWriterDateTimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3be39-103">Blob ライター日付/時刻形式。</span><span class="sxs-lookup"><span data-stu-id="3be39-103">Blob writer date time format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobWriterOverwriteFiles">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; BlobWriterOverwriteFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; BlobWriterOverwriteFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.BlobSink.BlobWriterOverwriteFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobWriterOverwriteFiles As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.BlobWriterOverwriteFiles : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.BlobSink.BlobWriterOverwriteFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3be39-104">Blob のライター ファイルを上書きします。</span><span class="sxs-lookup"><span data-stu-id="3be39-104">Blob writer overwrite files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyBehavior">
      <MemberSignature Language="C#" Value="public string CopyBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CopyBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.BlobSink.CopyBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property CopyBehavior As String" />
      <MemberSignature Language="F#" Value="member this.CopyBehavior : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.BlobSink.CopyBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3be39-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3be39-105">Optional.</span></span> <span data-ttu-id="3be39-106">コピー シンクのコピー動作の型。</span><span class="sxs-lookup"><span data-stu-id="3be39-106">The type of copy behavior for copy sink.</span></span>
            <see cref="T:Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>