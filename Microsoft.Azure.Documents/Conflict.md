<Type Name="Conflict" FullName="Microsoft.Azure.Documents.Conflict">
  <TypeSignature Language="C#" Value="public class Conflict : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Conflict extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Conflict" />
  <TypeSignature Language="VB.NET" Value="Public Class Conflict&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Conflict = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            これは、Azure Cosmos DB サービスの同時実行の非同期操作からの結果、競合するリソースです。
            </summary>
    <remarks>
            まれに、(挿入、置換、および削除)、非同期操作中に、バージョン競合が起きるリソース。
            競合しているリソースは、競合リソースとして保存されます。  
            競合リソースを調べることで、どの操作とリソースの競合が発生しました。 を決定できます。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Conflict ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Conflict.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Cosmos DB の Azure サービス内の競合クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResource&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetResource&lt;T&gt; () where T : Microsoft.Azure.Documents.Resourcenew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetResource&lt;.ctor (class Microsoft.Azure.Documents.Resource) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Conflict.GetResource``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetResource(Of T As {ResourceNew}) () As T" />
      <MemberSignature Language="F#" Value="member this.GetResource : unit -&gt; 'T (requires 'T :&gt; Microsoft.Azure.Documents.Resource and 'T : (new : unit -&gt; 'T))" Usage="conflict.GetResource " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">競合しているリソースの戻り値の型。</typeparam>
        <summary>
            Cosmos DB の Azure サービスで競合しているリソースを取得します。
            </summary>
        <returns>競合するリソースです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationKind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.OperationKind OperationKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.OperationKind OperationKind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Conflict.OperationKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationKind As OperationKind" />
      <MemberSignature Language="F#" Value="member this.OperationKind : Microsoft.Azure.Documents.OperationKind" Usage="Microsoft.Azure.Documents.Conflict.OperationKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.OperationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービスでの競合を発生させた操作を取得します。
            </summary>
        <value>
            値のいずれか、<see cref="P:Microsoft.Azure.Documents.Conflict.OperationKind" />列挙します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public Type ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Conflict.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As Type" />
      <MemberSignature Language="F#" Value="member this.ResourceType : Type" Usage="Microsoft.Azure.Documents.Conflict.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービスでは、競合するリソースの種類を取得します。
            </summary>
        <value>
            リソースの型。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceResourceId">
      <MemberSignature Language="C#" Value="public string SourceResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Conflict.SourceResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceResourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceResourceId : string" Usage="Microsoft.Azure.Documents.Conflict.SourceResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービスでの競合のリソース ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>