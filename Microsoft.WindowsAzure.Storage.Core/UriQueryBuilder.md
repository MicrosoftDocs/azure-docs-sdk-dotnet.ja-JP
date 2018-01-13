<Type Name="UriQueryBuilder" FullName="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder">
  <TypeSignature Language="C#" Value="public class UriQueryBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UriQueryBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class UriQueryBuilder" />
  <TypeSignature Language="F#" Value="type UriQueryBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            URI クエリ文字列を構築するための便利なクラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UriQueryBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UriQueryBuilder (Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.#ctor(Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (builder As UriQueryBuilder)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder : Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder -&gt; Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" Usage="new Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
      </Parameters>
      <Docs>
        <param name="builder">新しい <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> に要素がコピーされた <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />要素を格納するクラスが指定された対象からコピー<see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public virtual void Add (string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Add(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Add (name As String, value As String)" />
      <MemberSignature Language="F#" Value="abstract member Add : string * string -&gt; unit&#xA;override this.Add : string * string -&gt; unit" Usage="uriQueryBuilder.Add (name, value)" />
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
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">クエリ文字列名。</param>
        <param name="value">クエリ文字列の値。</param>
        <summary>
            URI のエスケープとクエリ文字列の値を追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRange">
      <MemberSignature Language="C#" Value="public void AddRange (System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;string,string&gt;&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddRange(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, string&gt;&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.AddRange(System.Collections.Generic.IEnumerable{System.Collections.Generic.KeyValuePair{System.String,System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddRange (parameters As IEnumerable(Of KeyValuePair(Of String, String)))" />
      <MemberSignature Language="F#" Value="member this.AddRange : seq&lt;System.Collections.Generic.KeyValuePair&lt;string, string&gt;&gt; -&gt; unit" Usage="uriQueryBuilder.AddRange parameters" />
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
        <Parameter Name="parameters" Type="System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;System.String,System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="parameters">クエリ文字列の名前/値ペアのセット</param>
        <summary>
            URI のエスケープを持つ複数のクエリ文字列値を追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddToUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri AddToUri (Microsoft.WindowsAzure.Storage.StorageUri storageUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.StorageUri AddToUri(class Microsoft.WindowsAzure.Storage.StorageUri storageUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.AddToUri(Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="F#" Value="member this.AddToUri : Microsoft.WindowsAzure.Storage.StorageUri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="uriQueryBuilder.AddToUri storageUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="storageUri">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />元の URI を含む、既存のすべてを含むクエリ パラメーター。</param>
        <summary>
            URI にクエリ パラメーターを追加します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />オブジェクトを新しいクエリ パラメーターが追加されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddToUri">
      <MemberSignature Language="C#" Value="public virtual Uri AddToUri (Uri uri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Uri AddToUri(class System.Uri uri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.AddToUri(System.Uri)" />
      <MemberSignature Language="F#" Value="abstract member AddToUri : Uri -&gt; Uri&#xA;override this.AddToUri : Uri -&gt; Uri" Usage="uriQueryBuilder.AddToUri uri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />既存のクエリ パラメーターを含む元の URI を含むオブジェクト。</param>
        <summary>
            URI にクエリ パラメーターを追加します。
            </summary>
        <returns>A<see cref="T:System.Uri" />オブジェクトを新しいクエリ パラメーターが追加されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddToUriCore">
      <MemberSignature Language="C#" Value="protected Uri AddToUriCore (Uri uri);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Uri AddToUriCore(class System.Uri uri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.AddToUriCore(System.Uri)" />
      <MemberSignature Language="F#" Value="member this.AddToUriCore : Uri -&gt; Uri" Usage="uriQueryBuilder.AddToUriCore uri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />既存のクエリ パラメーターを含む元の URI を含むオブジェクト。</param>
        <summary>
            URI にクエリ パラメーターを追加します。
            </summary>
        <returns>A<see cref="T:System.Uri" />オブジェクトを新しいクエリ パラメーターが追加されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsQueryStringName">
      <MemberSignature Language="C#" Value="public bool ContainsQueryStringName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool ContainsQueryStringName(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.ContainsQueryStringName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsQueryStringName (name As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.ContainsQueryStringName : string -&gt; bool" Usage="uriQueryBuilder.ContainsQueryStringName name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">クエリ文字列名</param>
        <summary>
            クエリ文字列名が、クエリ文字列内に存在するかどうかを判断します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public string this[string name] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(name As String) As String" />
      <MemberSignature Language="F#" Value="member this.Item(string) : string" Usage="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">クエリ文字列名。</param>
        <summary>
            指定された名前に関連付けられているクエリ文字列の値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Parameters" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クエリ パラメーターを格納します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="uriQueryBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            返します、 <see cref="T:System.String" /> URI を格納します。
            </summary>
        <returns>
            A <see cref="T:System.String" /> URI を格納します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>