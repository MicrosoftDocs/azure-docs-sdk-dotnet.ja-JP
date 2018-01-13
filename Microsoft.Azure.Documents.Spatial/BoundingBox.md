<Type Name="BoundingBox" FullName="Microsoft.Azure.Documents.Spatial.BoundingBox">
  <TypeSignature Language="C#" Value="public sealed class BoundingBox : IEquatable&lt;Microsoft.Azure.Documents.Spatial.BoundingBox&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BoundingBox extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.BoundingBox&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.BoundingBox" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BoundingBox&#xA;Implements IEquatable(Of BoundingBox)" />
  <TypeSignature Language="F#" Value="type BoundingBox = class&#xA;    interface IEquatable&lt;BoundingBox&gt;" />
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
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.BoundingBox&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.BoundingBoxJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Cosmos DB サービスのジオメトリの座標の範囲を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BoundingBox (Microsoft.Azure.Documents.Spatial.Position min, Microsoft.Azure.Documents.Spatial.Position max);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Spatial.Position min, class Microsoft.Azure.Documents.Spatial.Position max) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.BoundingBox.#ctor(Microsoft.Azure.Documents.Spatial.Position,Microsoft.Azure.Documents.Spatial.Position)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (min As Position, max As Position)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.BoundingBox : Microsoft.Azure.Documents.Spatial.Position * Microsoft.Azure.Documents.Spatial.Position -&gt; Microsoft.Azure.Documents.Spatial.BoundingBox" Usage="new Microsoft.Azure.Documents.Spatial.BoundingBox (min, max)" />
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
      <Parameters>
        <Parameter Name="min" Type="Microsoft.Azure.Documents.Spatial.Position" />
        <Parameter Name="max" Type="Microsoft.Azure.Documents.Spatial.Position" />
      </Parameters>
      <Docs>
        <param name="min">
            境界ボックスのすべての軸の最小値です。
            </param>
        <param name="max">
            境界ボックスのすべての軸の最高値です。
            </param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" /> Cosmos DB の Azure サービス内のクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.BoundingBox other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.BoundingBox other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.BoundingBox.Equals(Microsoft.Azure.Documents.Spatial.BoundingBox)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As BoundingBox) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.BoundingBox -&gt; bool" Usage="boundingBox.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.BoundingBox" />
      </Parameters>
      <Docs>
        <param name="other">
          <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" />この境界ボックスを比較します。</param>
        <summary>
            かどうかをこの<see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" />と等しい、 <paramref name="other" /> Cosmos DB の Azure サービスにします。
            </summary>
        <returns>
          <c>true</c>境界ボックスが等しい場合。 <c>false</c>それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.BoundingBox.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="boundingBox.Equals obj" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">現在のオブジェクトと比較するオブジェクト。 </param>
        <summary>
            決定するかどうか、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" />が現在と等しい<see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" />Cosmos DB の Azure サービスで。
            </summary>
        <returns>
            指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.BoundingBox.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="boundingBox.GetHashCode " />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ハッシュ関数として機能<see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" />Azure Cosmos DB サービスの種類。
            </summary>
        <returns>
            現在の <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" /> のハッシュ コード。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Max">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.Position Max { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Spatial.Position Max" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.BoundingBox.Max" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Max As Position" />
      <MemberSignature Language="F#" Value="member this.Max : Microsoft.Azure.Documents.Spatial.Position" Usage="Microsoft.Azure.Documents.Spatial.BoundingBox.Max" />
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.Position</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの境界ボックスのすべての軸の最大値を取得します。
            </summary>
        <value>
            境界ボックスのすべての軸の最高値です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Min">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.Position Min { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Spatial.Position Min" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.BoundingBox.Min" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Min As Position" />
      <MemberSignature Language="F#" Value="member this.Min : Microsoft.Azure.Documents.Spatial.Position" Usage="Microsoft.Azure.Documents.Spatial.BoundingBox.Min" />
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.Position</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの境界ボックスのすべての軸の最小値を取得します。
            </summary>
        <value>
            境界ボックスのすべての軸の最小値です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>