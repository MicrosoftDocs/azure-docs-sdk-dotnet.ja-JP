<Type Name="PartitionStrategy+Builder" FullName="Microsoft.Azure.Graphs.PartitionStrategy+Builder">
  <TypeSignature Language="C#" Value="public sealed class PartitionStrategy.Builder" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit PartitionStrategy/Builder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.PartitionStrategy.Builder" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionStrategy.Builder" />
  <TypeSignature Language="F#" Value="type PartitionStrategy.Builder = class" />
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
            パーティション分割の方法のビルダー クラス 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Builder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ビルダー メソッド
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.PartitionStrategy Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.PartitionStrategy Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.Create" />
      <MemberSignature Language="VB.NET" Value="Public Function Create () As PartitionStrategy" />
      <MemberSignature Language="F#" Value="member this.Create : unit -&gt; Microsoft.Azure.Graphs.PartitionStrategy" Usage="builder.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.PartitionStrategy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            PartitionStrategy オブジェクトを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.PartitionStrategy.Builder PartitionKey (string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.PartitionStrategy/Builder PartitionKey(string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.PartitionKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function PartitionKey (partitionKey As String) As PartitionStrategy.Builder" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string -&gt; Microsoft.Azure.Graphs.PartitionStrategy.Builder" Usage="builder.PartitionKey partitionKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.PartitionStrategy+Builder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey">To be added.</param>
        <summary>
            パーティション キーの名前を指定します。  これは、パーティションの値を含むプロパティのキーです。 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyString">
      <MemberSignature Language="C#" Value="public string PartitionKeyString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.PartitionStrategy.Builder.PartitionKeyString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyString As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyString : string" Usage="Microsoft.Azure.Graphs.PartitionStrategy.Builder.PartitionKeyString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Get アクセス操作子および set アクセス操作子の PartitionKey 名
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPartitions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.PartitionStrategy.Builder ReadPartitions (params object[] readPartitions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.PartitionStrategy/Builder ReadPartitions(object[] readPartitions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.ReadPartitions(System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPartitions (ParamArray readPartitions As Object()) As PartitionStrategy.Builder" />
      <MemberSignature Language="F#" Value="member this.ReadPartitions : obj[] -&gt; Microsoft.Azure.Graphs.PartitionStrategy.Builder" Usage="builder.ReadPartitions readPartitions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.PartitionStrategy+Builder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="readPartitions" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="readPartitions">To be added.</param>
        <summary>
            読み取りに、グラフのパーティションを指定します。  同時に複数のパーティションから読み取るための複数のパーティション キーを割り当てることができます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPartitionSet">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;object&gt; ReadPartitionSet { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;object&gt; ReadPartitionSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.PartitionStrategy.Builder.ReadPartitionSet" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadPartitionSet As HashSet(Of Object)" />
      <MemberSignature Language="F#" Value="member this.ReadPartitionSet : System.Collections.Generic.HashSet&lt;obj&gt;" Usage="Microsoft.Azure.Graphs.PartitionStrategy.Builder.ReadPartitionSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Get アクセス操作子および set アクセス操作子 ReadPartition セットの
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePartition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.PartitionStrategy.Builder WritePartition (object writePartition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.PartitionStrategy/Builder WritePartition(object writePartition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.WritePartition(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WritePartition (writePartition As Object) As PartitionStrategy.Builder" />
      <MemberSignature Language="F#" Value="member this.WritePartition : obj -&gt; Microsoft.Azure.Graphs.PartitionStrategy.Builder" Usage="builder.WritePartition writePartition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.PartitionStrategy+Builder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writePartition" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="writePartition">To be added.</param>
        <summary>
             書き込む、頂点、エッジ、および頂点のプロパティを追加するときに、パーティションの名前を指定します。  この名前は、任意のユーザー定義値であることができます。一度に単一のパーティションを記述することはのみです。
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePartitionObject">
      <MemberSignature Language="C#" Value="public object WritePartitionObject { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object WritePartitionObject" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.PartitionStrategy.Builder.WritePartitionObject" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WritePartitionObject As Object" />
      <MemberSignature Language="F#" Value="member this.WritePartitionObject : obj" Usage="Microsoft.Azure.Graphs.PartitionStrategy.Builder.WritePartitionObject" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Get アクセス操作子および set アクセス操作子 WritePartition の
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>