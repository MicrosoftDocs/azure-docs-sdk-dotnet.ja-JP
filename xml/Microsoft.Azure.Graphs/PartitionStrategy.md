<Type Name="PartitionStrategy" FullName="Microsoft.Azure.Graphs.PartitionStrategy">
  <TypeSignature Language="C#" Value="public sealed class PartitionStrategy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionStrategy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.PartitionStrategy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionStrategy" />
  <TypeSignature Language="F#" Value="type PartitionStrategy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="11e36-101">http://tinkerpop.apache.org/docs/current/reference/#_partitionstrategy TinkerPop 構文に沿って PartitionStrategy</span><span class="sxs-lookup"><span data-stu-id="11e36-101">http://tinkerpop.apache.org/docs/current/reference/#_partitionstrategy PartitionStrategy in line with TinkerPop Syntax</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Build">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Graphs.PartitionStrategy.Builder Build ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Graphs.PartitionStrategy/Builder Build() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Build" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Build () As PartitionStrategy.Builder" />
      <MemberSignature Language="F#" Value="static member Build : unit -&gt; Microsoft.Azure.Graphs.PartitionStrategy.Builder" Usage="Microsoft.Azure.Graphs.PartitionStrategy.Build " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.PartitionStrategy+Builder</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="11e36-102">パーティション分割の方法のビルダー オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="11e36-102">Creates the builder object for Partition Strategy</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public string GetPartitionKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetPartitionKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.GetPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionKey () As String" />
      <MemberSignature Language="F#" Value="member this.GetPartitionKey : unit -&gt; string" Usage="partitionStrategy.GetPartitionKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="11e36-103">パーティション キーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="11e36-103">Gets the partition key name</span></span>
            </summary>
        <returns><span data-ttu-id="11e36-104">文字列のパーティション キーの名前</span><span class="sxs-lookup"><span data-stu-id="11e36-104">string partition key name</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReadPartitions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;object&gt; GetReadPartitions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.HashSet`1&lt;object&gt; GetReadPartitions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.GetReadPartitions" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReadPartitions () As HashSet(Of Object)" />
      <MemberSignature Language="F#" Value="member this.GetReadPartitions : unit -&gt; System.Collections.Generic.HashSet&lt;obj&gt;" Usage="partitionStrategy.GetReadPartitions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="11e36-105">実行時に ReadPartitions のセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="11e36-105">Gets set of ReadPartitions at runtime</span></span>
            </summary>
        <returns><span data-ttu-id="11e36-106">読み取りのパーティションの文字列値を設定します。</span><span class="sxs-lookup"><span data-stu-id="11e36-106">Set of read partition string values</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWritePartition">
      <MemberSignature Language="C#" Value="public object GetWritePartition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance object GetWritePartition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.GetWritePartition" />
      <MemberSignature Language="VB.NET" Value="Public Function GetWritePartition () As Object" />
      <MemberSignature Language="F#" Value="member this.GetWritePartition : unit -&gt; obj" Usage="partitionStrategy.GetWritePartition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="11e36-107">書き込みのパーティションを取得します。</span><span class="sxs-lookup"><span data-stu-id="11e36-107">Gets the write partition</span></span>
            </summary>
        <returns><span data-ttu-id="11e36-108">文字列の書き込みパーティション値</span><span class="sxs-lookup"><span data-stu-id="11e36-108">string write partition value</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>