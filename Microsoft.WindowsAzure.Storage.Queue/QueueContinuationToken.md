<Type Name="QueueContinuationToken" FullName="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken">
  <TypeSignature Language="C#" Value="public sealed class QueueContinuationToken : Microsoft.WindowsAzure.Storage.IContinuationToken, System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit QueueContinuationToken extends System.Object implements class Microsoft.WindowsAzure.Storage.IContinuationToken, class System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QueueContinuationToken&#xA;Implements IContinuationToken, IXmlSerializable" />
  <TypeSignature Language="F#" Value="type QueueContinuationToken = class&#xA;    interface IContinuationToken&#xA;    interface IXmlSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.IContinuationToken</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Xml.Serialization.IXmlSerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Xml.Serialization.XmlRoot("ContinuationToken", IsNullable=false)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            キュー サービスによって返される継続トークンを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueContinuationToken ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchema">
      <MemberSignature Language="C#" Value="public System.Xml.Schema.XmlSchema GetSchema ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Xml.Schema.XmlSchema GetSchema() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken.GetSchema" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSchema () As XmlSchema" />
      <MemberSignature Language="F#" Value="abstract member GetSchema : unit -&gt; System.Xml.Schema.XmlSchema&#xA;override this.GetSchema : unit -&gt; System.Xml.Schema.XmlSchema" Usage="queueContinuationToken.GetSchema " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.GetSchema</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.Schema.XmlSchema</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトの XML 表現を取得します。
            </summary>
        <returns>
            <see cref="M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)" /> メソッドによって生成され <see cref="M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)" /> メソッドによって処理されるオブジェクトの XML 表現を記述する <see cref="T:System.Xml.Schema.XmlSchema" />。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken.NextMarker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の結果を継続するための次のマーカー<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />列挙操作します。
            </summary>
        <value>NextMarker 値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadXml">
      <MemberSignature Language="C#" Value="public void ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken.ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReadXml (reader As XmlReader)" />
      <MemberSignature Language="F#" Value="abstract member ReadXml : System.Xml.XmlReader -&gt; unit&#xA;override this.ReadXml : System.Xml.XmlReader -&gt; unit" Usage="queueContinuationToken.ReadXml reader" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><see cref="T:System.Xml.XmlReader" />継続トークンを逆シリアル化するストリームします。</param>
        <summary>
            XML 表現からシリアル化可能な継続トークンを生成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.StorageLocation&gt; TargetLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.StorageLocation&gt; TargetLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken.TargetLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLocation As Nullable(Of StorageLocation)" />
      <MemberSignature Language="F#" Value="member this.TargetLocation : Nullable&lt;Microsoft.WindowsAzure.Storage.StorageLocation&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken.TargetLocation" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IContinuationToken.TargetLocation</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.StorageLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または継続トークンが適用される記憶域の場所を設定します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteXml">
      <MemberSignature Language="C#" Value="public void WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken.WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub WriteXml (writer As XmlWriter)" />
      <MemberSignature Language="F#" Value="abstract member WriteXml : System.Xml.XmlWriter -&gt; unit&#xA;override this.WriteXml : System.Xml.XmlWriter -&gt; unit" Usage="queueContinuationToken.WriteXml writer" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer"><see cref="T:System.Xml.XmlWriter" />ストリームの継続トークンのシリアル化します。</param>
        <summary>
            シリアル化可能な継続トークンを XML 表現に変換します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>