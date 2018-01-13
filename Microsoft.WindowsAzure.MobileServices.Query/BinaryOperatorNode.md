<Type Name="BinaryOperatorNode" FullName="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode">
  <TypeSignature Language="C#" Value="public sealed class BinaryOperatorNode : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BinaryOperatorNode extends Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BinaryOperatorNode&#xA;Inherits QueryNode" />
  <TypeSignature Language="F#" Value="type BinaryOperatorNode = class&#xA;    inherit QueryNode" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            二項演算子を表すノードをクエリします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BinaryOperatorNode (Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind kind, Microsoft.WindowsAzure.MobileServices.Query.QueryNode left, Microsoft.WindowsAzure.MobileServices.Query.QueryNode right);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind kind, class Microsoft.WindowsAzure.MobileServices.Query.QueryNode left, class Microsoft.WindowsAzure.MobileServices.Query.QueryNode right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.#ctor(Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind,Microsoft.WindowsAzure.MobileServices.Query.QueryNode,Microsoft.WindowsAzure.MobileServices.Query.QueryNode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (kind As BinaryOperatorKind, left As QueryNode, right As QueryNode)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode : Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind * Microsoft.WindowsAzure.MobileServices.Query.QueryNode * Microsoft.WindowsAzure.MobileServices.Query.QueryNode -&gt; Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode" Usage="new Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode (kind, left, right)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind" />
        <Parameter Name="left" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
        <Parameter Name="right" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
      </Parameters>
      <Docs>
        <param name="kind">このノードの種類。</param>
        <param name="left">左オペランド。</param>
        <param name="right">右オペランド。</param>
        <summary>
            インスタンスを初期化します<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Accept&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T Accept&lt;T&gt; (Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt; visitor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T Accept&lt;T&gt;(class Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1&lt;!!T&gt; visitor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.Accept``1(Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Accept(Of T) (visitor As QueryNodeVisitor(Of T)) As T" />
      <MemberSignature Language="F#" Value="override this.Accept : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;'T&gt; -&gt; 'T" Usage="binaryOperatorNode.Accept visitor" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="visitor" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">ビジターがこのトークンにアクセスした後に戻る型。</typeparam>
        <param name="visitor">ビジター インターフェイスの実装。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" /> ツリーをたどる <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" /> を受け入れます。
            </summary>
        <returns>ビジターのパラメーターの型によって型が決まるオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public override Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Kind As QueryNodeKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind" Usage="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クエリ ノードの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeftOperand">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.QueryNode LeftOperand { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Query.QueryNode LeftOperand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.LeftOperand" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeftOperand As QueryNode" />
      <MemberSignature Language="F#" Value="member this.LeftOperand : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" Usage="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.LeftOperand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            左オペランドを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorKind">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind OperatorKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind OperatorKind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.OperatorKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperatorKind As BinaryOperatorKind" />
      <MemberSignature Language="F#" Value="member this.OperatorKind : Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind" Usage="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.OperatorKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このノードが表す演算子。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RightOperand">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.QueryNode RightOperand { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Query.QueryNode RightOperand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.RightOperand" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RightOperand As QueryNode" />
      <MemberSignature Language="F#" Value="member this.RightOperand : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" Usage="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.RightOperand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            右オペランドを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>