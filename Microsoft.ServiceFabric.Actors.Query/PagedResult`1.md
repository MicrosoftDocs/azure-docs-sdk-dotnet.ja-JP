<Type Name="PagedResult&lt;T&gt;" FullName="Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;T&gt;">
  <TypeSignature Language="C#" Value="public sealed class PagedResult&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PagedResult`1&lt;class T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Query.PagedResult`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PagedResult(Of T)" />
  <TypeSignature Language="F#" Value="type PagedResult&lt;'T (requires 'T : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="PagedResult", Namespace="urn:actors")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Collections.Generic.List`1&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T">
      <see cref="T:System.Type" />項目のこのクエリ結果が含まれています。</typeparam>
    <summary>
            アクター クエリの呼び出しの結果を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PagedResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Query.PagedResult`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Actors.Query.PagedResult`1" /> クラスの新しいインスタンスを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Query.ContinuationToken ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Query.ContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Query.PagedResult`1.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As ContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.ServiceFabric.Actors.Query.ContinuationToken with get, set" Usage="Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;'T (requires 'T : null)&gt;.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=false, Name="ContinuationToken", Order=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Query.ContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または他のアイテムをメソッドを呼び出して、再度フェッチする必要があるかどうかを示す継続トークンを設定します。
            </summary>
        <value>ConinutationToken 示す場合、メソッドで返される、<see cref="T:Microsoft.ServiceFabric.Actors.Query.PagedResult`1" />より多くの結果を取得するもう一度呼び出すとする必要があります </value>
        <remarks>Null 値が結果には、すべてのアイテムとメソッドの呼び出しはありませんが含まれている継続トークンの場合を他のアイテムをフェッチできるようにする必要があります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Items">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; Items { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; Items" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Query.PagedResult`1.Items" />
      <MemberSignature Language="VB.NET" Value="Public Property Items As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="member this.Items : seq&lt;'T (requires 'T : null)&gt; with get, set" Usage="Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;'T (requires 'T : null)&gt;.Items" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="Items", Order=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または結果を反復処理する列挙子を設定します。
            </summary>
        <value>列挙子をコレクションに対する単純な反復処理をサポートします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>