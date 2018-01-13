<Type Name="Position" FullName="Microsoft.Azure.Documents.Spatial.Position">
  <TypeSignature Language="C#" Value="public sealed class Position : IEquatable&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Position extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Position" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Position&#xA;Implements IEquatable(Of Position)" />
  <TypeSignature Language="F#" Value="type Position = class&#xA;    interface IEquatable&lt;Position&gt;" />
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
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.Position&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.PositionJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            位置は、Azure Cosmos DB サービスの数値の配列で表されます。 存在する必要がありますには、少なくとも 2 つの要素、および詳細があります。
            </para>
      <para>
            要素の順序は、経度、緯度、高度に従う必要があります。
            解釈および追加の要素の意味は、アプリケーションの任意の数の要素を許可します。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Position (System.Collections.Generic.IList&lt;double&gt; coordinates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;float64&gt; coordinates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.#ctor(System.Collections.Generic.IList{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinates As IList(Of Double))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Position : System.Collections.Generic.IList&lt;double&gt; -&gt; Microsoft.Azure.Documents.Spatial.Position" Usage="new Microsoft.Azure.Documents.Spatial.Position coordinates" />
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
        <Parameter Name="coordinates" Type="System.Collections.Generic.IList&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinates">
            位置の値。
            </param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> Cosmos DB の Azure サービス内のクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Position (double longitude, double latitude);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(float64 longitude, float64 latitude) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.#ctor(System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (longitude As Double, latitude As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Position : double * double -&gt; Microsoft.Azure.Documents.Spatial.Position" Usage="new Microsoft.Azure.Documents.Spatial.Position (longitude, latitude)" />
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
        <Parameter Name="longitude" Type="System.Double" />
        <Parameter Name="latitude" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="longitude">
            経度の値。
            </param>
        <param name="latitude">
            緯度の値。
            </param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> Cosmos DB の Azure サービス内のクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Position (double longitude, double latitude, Nullable&lt;double&gt; altitude);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(float64 longitude, float64 latitude, valuetype System.Nullable`1&lt;float64&gt; altitude) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.#ctor(System.Double,System.Double,System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (longitude As Double, latitude As Double, altitude As Nullable(Of Double))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Position : double * double * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Documents.Spatial.Position" Usage="new Microsoft.Azure.Documents.Spatial.Position (longitude, latitude, altitude)" />
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
        <Parameter Name="longitude" Type="System.Double" />
        <Parameter Name="latitude" Type="System.Double" />
        <Parameter Name="altitude" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="longitude">
            経度の値。
            </param>
        <param name="latitude">
            緯度の値。
            </param>
        <param name="altitude">
            省略可能な高度の値です。
            </param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> Cosmos DB の Azure サービス内のクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Altitude">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Altitude { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Altitude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Position.Altitude" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Altitude As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Altitude : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Documents.Spatial.Position.Altitude" />
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
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの省略可能な高度を取得します。
            </summary>
        <value>
            高度の値です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Coordinates">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;double&gt; Coordinates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;float64&gt; Coordinates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Position.Coordinates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Coordinates As ReadOnlyCollection(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Coordinates : System.Collections.ObjectModel.ReadOnlyCollection&lt;double&gt;" Usage="Microsoft.Azure.Documents.Spatial.Position.Coordinates" />
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
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの位置座標を取得します。
            </summary>
        <value>
            値を調整します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.Position other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.Position other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.Equals(Microsoft.Azure.Documents.Spatial.Position)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Position) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.Position -&gt; bool" Usage="position.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.Position" />
      </Parameters>
      <Docs>
        <param name="other">
          <see cref="T:Microsoft.Azure.Documents.Spatial.Position" />これと比較する<see cref="T:Microsoft.Azure.Documents.Spatial.Position" />です。</param>
        <summary>
            かどうかをこの<see cref="T:Microsoft.Azure.Documents.Spatial.Position" />と等しい、 <paramref name="other" /> Cosmos DB の Azure サービスにします。
            </summary>
        <returns>
          <c>true</c>オブジェクトが等しい場合。 <c>false</c>それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="position.Equals obj" />
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
        <param name="obj"><see cref="T:Microsoft.Azure.Documents.Spatial.Position" />現在のオブジェクトと比較します。 </param>
        <summary>
            決定するかどうか、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.Position" />が現在と等しい<see cref="T:Microsoft.Azure.Documents.Spatial.Position" />Cosmos DB の Azure サービスで。
            </summary>
        <returns>
            true の場合、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.Position" />が現在のオブジェクトと等しい場合は false。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="position.GetHashCode " />
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
            ハッシュ関数として機能、 <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> Azure Cosmos DB サービスの種類。
            </summary>
        <returns>
            現在の <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> のハッシュ コード。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Latitude">
      <MemberSignature Language="C#" Value="public double Latitude { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Latitude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Position.Latitude" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Latitude As Double" />
      <MemberSignature Language="F#" Value="member this.Latitude : double" Usage="Microsoft.Azure.Documents.Spatial.Position.Latitude" />
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
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの緯度を取得します。
            </summary>
        <value>
            緯度の値。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Longitude">
      <MemberSignature Language="C#" Value="public double Longitude { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Longitude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Position.Longitude" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Longitude As Double" />
      <MemberSignature Language="F#" Value="member this.Longitude : double" Usage="Microsoft.Azure.Documents.Spatial.Position.Longitude" />
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
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの経度を取得します。
            </summary>
        <value>
            経度の値。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>