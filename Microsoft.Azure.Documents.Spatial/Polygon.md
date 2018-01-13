<Type Name="Polygon" FullName="Microsoft.Azure.Documents.Spatial.Polygon">
  <TypeSignature Language="C#" Value="public sealed class Polygon : Microsoft.Azure.Documents.Spatial.Geometry, IEquatable&lt;Microsoft.Azure.Documents.Spatial.Polygon&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Polygon extends Microsoft.Azure.Documents.Spatial.Geometry implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.Polygon&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Polygon" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Polygon&#xA;Inherits Geometry&#xA;Implements IEquatable(Of Polygon)" />
  <TypeSignature Language="F#" Value="type Polygon = class&#xA;    inherit Geometry&#xA;    interface IEquatable&lt;Polygon&gt;" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Spatial.Geometry</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.Polygon&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            Azure Cosmos DB サービスの多角形 geometry クラスです。
            </para>
      <para>
            多角形は、「多角形のリング」のセットで表されます。 それぞれのリングが閉じているコマンドライン文字列。
            最初のリングでは、外部リングを定義します。 後続のすべてのリングは、外部リングで「口」を定義します。
            </para>
      <para>
            リングは、左側にある規則を使用して指定する必要があります。 そのポイントの順序でリングを走査する内部、多角形領域の左側にされていることになります。
            </para>
    </summary>
    <remarks>To be added.</remarks>
    <example>
            この例では、地球のごく一部の内容を含む多角形を定義する方法を示します。
            <code language="c#"><![CDATA[
            var polygon = new Polygon(
                    new[]
                    {
                        new Position(20.0, 20.0),
                        new Position(30.0, 20.0),
                        new Position(30.0, 30.0),
                        new Position(20.0, 30.0)
                        new Position(20.0, 20.0)
                    });
            ]]></code></example>
    <example>
            この例は複数の半球に収まらない領域の内容を含む多角形を定義する方法を示します: (座標の注文だけが取り消されたことに注意してください)。
            <code language="c#"><![CDATA[
            var polygon = new Polygon(
            new[]
                    {
                    new Position(20.0, 20.0),
                        new Position(20.0, 30.0),
                        new Position(30.0, 30.0),
                        new Position(30.0, 20.0)
                        new Position(20.0, 20.0)
                        });
                    ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.LinearRing})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rings As IList(Of LinearRing))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon rings" />
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
        <Parameter Name="rings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
      </Parameters>
      <Docs>
        <param name="rings">
          <para>
            多角形のリングします。
            </para>
          <para>
            最初のリングが外部リングでします。 次のリングは、多角形で '穴' を定義します。
            </para>
        </param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Cosmos DB の Azure サービス内のクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; externalRingPositions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; externalRingPositions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.Position})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (externalRingPositions As IList(Of Position))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon externalRingPositions" />
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
        <Parameter Name="externalRingPositions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" />
      </Parameters>
      <Docs>
        <param name="externalRingPositions">
            外部の多角形のリングの座標です。
            </param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Cosmos DB の Azure サービスで外部リング (多角形が含まれていない穴には) からのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings, Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings, class Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.LinearRing},Microsoft.Azure.Documents.Spatial.GeometryParams)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; * Microsoft.Azure.Documents.Spatial.GeometryParams -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon (rings, geometryParams)" />
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
        <Parameter Name="rings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
        <Parameter Name="geometryParams" Type="Microsoft.Azure.Documents.Spatial.GeometryParams" />
      </Parameters>
      <Docs>
        <param name="rings">
            多角形のリングします。
            </param>
        <param name="geometryParams">
            追加のジオメトリのパラメーターです。
            </param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Cosmos DB の Azure サービス内のクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.Polygon other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.Polygon other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.Equals(Microsoft.Azure.Documents.Spatial.Polygon)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Polygon) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.Polygon -&gt; bool" Usage="polygon.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.Polygon" />
      </Parameters>
      <Docs>
        <param name="other">
          <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />これと比較する<see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />です。</param>
        <summary>
            かどうかをこの<see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />と等しい、 <paramref name="other" /> Cosmos DB の Azure サービスにします。
            </summary>
        <returns>
          <c>true</c>オブジェクトが等しい場合。 <c>false</c>それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="polygon.Equals obj" />
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
            決定するかどうか、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />が現在と等しい<see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />Cosmos DB の Azure サービスで。
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="polygon.GetHashCode " />
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
            ハッシュ関数として機能、 <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Azure Cosmos DB サービスの種類。
            </summary>
        <returns>
            現在の <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> のハッシュ コード。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rings">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; Rings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; Rings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Polygon.Rings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Rings As ReadOnlyCollection(Of LinearRing)" />
      <MemberSignature Language="F#" Value="member this.Rings : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" Usage="Microsoft.Azure.Documents.Spatial.Polygon.Rings" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("coordinates", Order=1, Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの多角形のリングを取得します。
            </summary>
        <value>
            多角形のリングします。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>