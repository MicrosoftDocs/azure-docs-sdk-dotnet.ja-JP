<Type Name="OperationContext" FullName="Microsoft.Azure.Batch.Common.OperationContext">
  <TypeSignature Language="C#" Value="public sealed class OperationContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OperationContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.OperationContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OperationContext" />
  <TypeSignature Language="F#" Value="type OperationContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5dc4c-101">Batch service への要求のコンテキストを表し、その実行に関する追加情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="5dc4c-101">Represents the context for a request to the Batch service and provides additional information about its execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.OperationContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5dc4c-102"><see cref="T:Microsoft.Azure.Batch.Common.OperationContext" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5dc4c-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Common.OperationContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResults">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Common.RequestResult&gt; RequestResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Common.RequestResult&gt; RequestResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.OperationContext.RequestResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestResults As IList(Of RequestResult)" />
      <MemberSignature Language="F#" Value="member this.RequestResults : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Common.RequestResult&gt;" Usage="Microsoft.Azure.Batch.Common.OperationContext.RequestResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Common.RequestResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5dc4c-103">取得または現在の操作の要求の結果の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="5dc4c-103">Gets or sets the list of request results for the current operation.</span></span>  <span data-ttu-id="5dc4c-104">各<see cref="T:Microsoft.Azure.Batch.Common.RequestResult" />サーバーに送信される 1 つの要求に対応しています。</span><span class="sxs-lookup"><span data-stu-id="5dc4c-104">Each <see cref="T:Microsoft.Azure.Batch.Common.RequestResult" /> corresponds to one request sent to the server.</span></span>  <span data-ttu-id="5dc4c-105">再試行の場合は、この一覧に複数の項目が可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5dc4c-105">There may be more than one item in this list in the case of retries.</span></span>
            </summary>
        <value><span data-ttu-id="5dc4c-106"><see cref="T:System.Collections.IList" />オブジェクトを含む<see cref="T:Microsoft.Azure.Batch.Common.RequestResult" />を現在の操作によって作成された要求の結果を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5dc4c-106">An <see cref="T:System.Collections.IList" /> object that contains <see cref="T:Microsoft.Azure.Batch.Common.RequestResult" /> objects that represent the request results created by the current operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>