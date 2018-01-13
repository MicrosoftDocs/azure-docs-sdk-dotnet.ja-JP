<Type Name="Operation" FullName="Microsoft.Azure.DataLake.Store.Operation">
  <TypeSignature Language="C#" Value="public sealed class Operation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Operation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.Operation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Operation" />
  <TypeSignature Language="F#" Value="type Operation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2bdf5-101">Http 要求に対するすべての使用可能な操作のディクショナリを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="2bdf5-101">Lists a dictionary of all available Operations for a Http request</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Method">
      <MemberSignature Language="C#" Value="public string Method { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Method" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Operation.Method" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Method As String" />
      <MemberSignature Language="F#" Value="member this.Method : string" Usage="Microsoft.Azure.DataLake.Store.Operation.Method" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2bdf5-102">HTTP メソッド、操作を GET と PUT または POST のように使用します。</span><span class="sxs-lookup"><span data-stu-id="2bdf5-102">HTTP method the operation uses like GET/PUT/POST</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Namespace">
      <MemberSignature Language="C#" Value="public string Namespace { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Namespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Operation.Namespace" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Namespace As String" />
      <MemberSignature Language="F#" Value="member this.Namespace : string" Usage="Microsoft.Azure.DataLake.Store.Operation.Namespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2bdf5-103">どのようなハンドラー WebHdfs または WebHdfsExt が使われます</span><span class="sxs-lookup"><span data-stu-id="2bdf5-103">What handler it uses WebHdfs or WebHdfsExt</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.Dictionary&lt;Microsoft.Azure.DataLake.Store.OperationCodes,Microsoft.Azure.DataLake.Store.Operation&gt; Operations;" />
      <MemberSignature Language="ILAsm" Value=".field public static class System.Collections.Generic.Dictionary`2&lt;valuetype Microsoft.Azure.DataLake.Store.OperationCodes, class Microsoft.Azure.DataLake.Store.Operation&gt; Operations" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.Operation.Operations" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operations As Dictionary(Of OperationCodes, Operation) " />
      <MemberSignature Language="F#" Value=" staticval mutable Operations : System.Collections.Generic.Dictionary&lt;Microsoft.Azure.DataLake.Store.OperationCodes, Microsoft.Azure.DataLake.Store.Operation&gt;" Usage="Microsoft.Azure.DataLake.Store.Operation.Operations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;Microsoft.Azure.DataLake.Store.OperationCodes,Microsoft.Azure.DataLake.Store.Operation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2bdf5-104">操作を含むディクショナリ</span><span class="sxs-lookup"><span data-stu-id="2bdf5-104">Dictionary containing the Operations</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresBody">
      <MemberSignature Language="C#" Value="public bool RequiresBody { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresBody" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Operation.RequiresBody" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequiresBody As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresBody : bool" Usage="Microsoft.Azure.DataLake.Store.Operation.RequiresBody" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2bdf5-105">この操作の http 要求が要求本文 (データ) を必要とするかどうか</span><span class="sxs-lookup"><span data-stu-id="2bdf5-105">Whether the http request for this operation requires request body (data)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnsBody">
      <MemberSignature Language="C#" Value="public bool ReturnsBody { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReturnsBody" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.Operation.ReturnsBody" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReturnsBody As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReturnsBody : bool" Usage="Microsoft.Azure.DataLake.Store.Operation.ReturnsBody" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2bdf5-106">この操作の http 応答が応答本文 (データ) を返すかどうか</span><span class="sxs-lookup"><span data-stu-id="2bdf5-106">Whether the http response for this operation returns response body (data)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>