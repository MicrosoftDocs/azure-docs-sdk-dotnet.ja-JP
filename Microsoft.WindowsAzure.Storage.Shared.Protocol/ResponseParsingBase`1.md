<Type Name="ResponseParsingBase&lt;T&gt;" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class ResponseParsingBase&lt;T&gt; : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ResponseParsingBase`1&lt;T&gt; extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ResponseParsingBase(Of T)&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ResponseParsingBase&lt;'T&gt; = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T">解析する型。</typeparam>
    <summary>
            記憶域のサービス操作からの XML ストリームの解析を内部的に使用される基本クラスを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ResponseParsingBase (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt; : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;" Usage="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt; stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream">解析されるストリーム。</param>
        <summary>
            ResponseParsingBase クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="allObjectsParsed">
      <MemberSignature Language="C#" Value="protected bool allObjectsParsed;" />
      <MemberSignature Language="ILAsm" Value=".field family bool allObjectsParsed" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.allObjectsParsed" />
      <MemberSignature Language="VB.NET" Value="Protected allObjectsParsed As Boolean " />
      <MemberSignature Language="F#" Value="val mutable allObjectsParsed : bool" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;.allObjectsParsed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            解析のすべてのオブジェクトが消費されていることを示します。 このフィールドは、予約されておりは使用できません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="responseParsingBase.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アンマネージ リソースの解放またはリセットに関連付けられているアプリケーション定義のタスクを実行します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="responseParsingBase.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <c>True</c>マネージ コードとアンマネージ リソースを解放する場合は、 <c>false</c>です。</param>
        <summary>
            解放、リリース、またはアンマネージ リソース、および省略可能な管理対象リソースのリセットに関連付けられているアプリケーション定義のタスクを実行します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectsToParse">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IEnumerable&lt;T&gt; ObjectsToParse { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ObjectsToParse" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.ObjectsToParse" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ObjectsToParse As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="member this.ObjectsToParse : seq&lt;'T&gt;" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;.ObjectsToParse" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            解析可能では、オブジェクトを取得します。 このメソッドは予約されているため、使用できません。
            </summary>
        <value>解析するオブジェクトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="outstandingObjectsToParse">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IList&lt;T&gt; outstandingObjectsToParse;" />
      <MemberSignature Language="ILAsm" Value=".field family class System.Collections.Generic.IList`1&lt;!T&gt; outstandingObjectsToParse" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.outstandingObjectsToParse" />
      <MemberSignature Language="VB.NET" Value="Protected outstandingObjectsToParse As IList(Of T) " />
      <MemberSignature Language="F#" Value="val mutable outstandingObjectsToParse : System.Collections.Generic.IList&lt;'T&gt;" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;.outstandingObjectsToParse" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            解析されていないすべてのオブジェクトを格納します。 このフィールドは、予約されておりは使用できません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;T&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ParseXml () As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ParseXml : unit -&gt; seq&lt;'T&gt;" Usage="responseParsingBase.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            XML 応答を解析します。 このメソッドは予約されているため、使用できません。
            </summary>
        <returns>列挙可能なオブジェクトのコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="reader">
      <MemberSignature Language="C#" Value="protected System.Xml.XmlReader reader;" />
      <MemberSignature Language="ILAsm" Value=".field family class System.Xml.XmlReader reader" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.reader" />
      <MemberSignature Language="VB.NET" Value="Protected reader As XmlReader " />
      <MemberSignature Language="F#" Value="val mutable reader : System.Xml.XmlReader" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;.reader" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlReader</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            解析に使用するリーダー。 このフィールドは、予約されておりは使用できません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Variable">
      <MemberSignature Language="C#" Value="protected void Variable (ref bool consumable);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Variable(bool&amp; consumable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.Variable(System.Boolean@)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Variable (ByRef consumable As Boolean)" />
      <MemberSignature Language="F#" Value="member this.Variable :  -&gt; unit" Usage="responseParsingBase.Variable consumable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumable" Type="System.Boolean&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="consumable">
          <c>True</c>オブジェクトが使用できるようにします。</param>
        <summary>
            このメソッドは予約されているため、使用できません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>