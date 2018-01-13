<Type Name="BlobSource" FullName="Microsoft.Azure.Management.DataFactories.Models.BlobSource">
  <TypeSignature Language="C#" Value="public class BlobSource : Microsoft.Azure.Management.DataFactories.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobSource extends Microsoft.Azure.Management.DataFactories.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.BlobSource" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type BlobSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3836f-101">コピー アクティビティ blob ソース。</span><span class="sxs-lookup"><span data-stu-id="3836f-101">A copy activity blob source.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.BlobSource.#ctor" />
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
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.BlobSource.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Recursive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.BlobSource.Recursive" />
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
            <span data-ttu-id="3836f-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3836f-102">Optional.</span></span> <span data-ttu-id="3836f-103">True の場合、フォルダーのパスの下のファイルには、再帰的が読み取られます。</span><span class="sxs-lookup"><span data-stu-id="3836f-103">If true, files under the folder path will be read recursively.</span></span>        
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipHeaderLineCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SkipHeaderLineCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SkipHeaderLineCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.BlobSource.SkipHeaderLineCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipHeaderLineCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SkipHeaderLineCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.BlobSource.SkipHeaderLineCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3836f-104">各 blob からスキップするヘッダー行の数。</span><span class="sxs-lookup"><span data-stu-id="3836f-104">Number of header lines to skip from each blob.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TreatEmptyAsNull">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; TreatEmptyAsNull { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; TreatEmptyAsNull" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.BlobSource.TreatEmptyAsNull" />
      <MemberSignature Language="VB.NET" Value="Public Property TreatEmptyAsNull As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.TreatEmptyAsNull : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.BlobSource.TreatEmptyAsNull" />
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
            <span data-ttu-id="3836f-105">Null と空に処理します。</span><span class="sxs-lookup"><span data-stu-id="3836f-105">Treat empty as null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>