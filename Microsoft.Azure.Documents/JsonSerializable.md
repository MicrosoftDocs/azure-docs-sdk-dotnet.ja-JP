<Type Name="JsonSerializable" FullName="Microsoft.Azure.Documents.JsonSerializable">
  <TypeSignature Language="C#" Value="public abstract class JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit JsonSerializable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class JsonSerializable" />
  <TypeSignature Language="F#" Value="type JsonSerializable = class" />
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
  <Interfaces />
  <Docs>
    <summary>
            Azure Cosmos DB データベース オブジェクトの基本クラスを表し、シリアル化すると、JSON から逆シリアル化メソッドを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public virtual void LoadFrom (Newtonsoft.Json.JsonReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void LoadFrom(class Newtonsoft.Json.JsonReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFrom(Newtonsoft.Json.JsonReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub LoadFrom (reader As JsonReader)" />
      <MemberSignature Language="F#" Value="abstract member LoadFrom : Newtonsoft.Json.JsonReader -&gt; unit&#xA;override this.LoadFrom : Newtonsoft.Json.JsonReader -&gt; unit" Usage="jsonSerializable.LoadFrom reader" />
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
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
      </Parameters>
      <Docs>
        <param name="reader">この JSON リーダーからオブジェクトを読み込みます。</param>
        <summary>
            Azure Cosmos DB サービスの指定した JSON リーダーからオブジェクトを読み込みます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public virtual void LoadFrom (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonSerializerSettings serializerSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void LoadFrom(class Newtonsoft.Json.JsonReader reader, class Newtonsoft.Json.JsonSerializerSettings serializerSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFrom(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonSerializerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub LoadFrom (reader As JsonReader, serializerSettings As JsonSerializerSettings)" />
      <MemberSignature Language="F#" Value="abstract member LoadFrom : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonSerializerSettings -&gt; unit&#xA;override this.LoadFrom : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonSerializerSettings -&gt; unit" Usage="jsonSerializable.LoadFrom (reader, serializerSettings)" />
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
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="serializerSettings" Type="Newtonsoft.Json.JsonSerializerSettings" />
      </Parameters>
      <Docs>
        <param name="reader">この JSON リーダーからオブジェクトを読み込みます。</param>
        <param name="serializerSettings">使用する JsonSerializerSettings。</param>
        <summary>
            Azure Cosmos DB サービスの指定した JSON リーダーからオブジェクトを読み込みます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T LoadFrom&lt;T&gt; (System.IO.Stream stream) where T : Microsoft.Azure.Documents.JsonSerializablenew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T LoadFrom&lt;.ctor (class Microsoft.Azure.Documents.JsonSerializable) T&gt;(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFrom``1(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.IO.Stream -&gt; 'T (requires 'T :&gt; Microsoft.Azure.Documents.JsonSerializable and 'T : (new : unit -&gt; 'T))" Usage="Microsoft.Azure.Documents.JsonSerializable.LoadFrom stream" />
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
            <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <typeparam name="T">返されるオブジェクトの型。</typeparam>
        <param name="stream">読み込むストリーム。</param>
        <summary>
            Cosmos DB の Azure サービスで指定したストリームからオブジェクトを読み込みます。
            </summary>
        <returns>オブジェクトは、指定したストリームから読み込まれます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFromWithConstructor&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T LoadFromWithConstructor&lt;T&gt; (System.IO.Stream stream, Func&lt;T&gt; constructorFunction);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T LoadFromWithConstructor&lt;T&gt;(class System.IO.Stream stream, class System.Func`1&lt;!!T&gt; constructorFunction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFromWithConstructor``1(System.IO.Stream,System.Func{``0})" />
      <MemberSignature Language="F#" Value="static member LoadFromWithConstructor : System.IO.Stream * Func&lt;'T&gt; -&gt; 'T" Usage="Microsoft.Azure.Documents.JsonSerializable.LoadFromWithConstructor (stream, constructorFunction)" />
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
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="constructorFunction" Type="System.Func&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">オブジェクトの型。</typeparam>
        <param name="stream">読み込むストリーム。</param>
        <param name="constructorFunction">返されるオブジェクトに使用されるコンス トラクターです。</param>
        <summary>
            Azure Cosmos DB サービスの特定のコンス トラクターを使用して、指定されたストリームを逆シリアル化します。
            </summary>
        <returns>オブジェクトは、指定したストリームから読み込まれます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFromWithConstructor&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T LoadFromWithConstructor&lt;T&gt; (System.IO.Stream stream, Func&lt;T&gt; constructorFunction, Newtonsoft.Json.JsonSerializerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T LoadFromWithConstructor&lt;T&gt;(class System.IO.Stream stream, class System.Func`1&lt;!!T&gt; constructorFunction, class Newtonsoft.Json.JsonSerializerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.LoadFromWithConstructor``1(System.IO.Stream,System.Func{``0},Newtonsoft.Json.JsonSerializerSettings)" />
      <MemberSignature Language="F#" Value="static member LoadFromWithConstructor : System.IO.Stream * Func&lt;'T&gt; * Newtonsoft.Json.JsonSerializerSettings -&gt; 'T" Usage="Microsoft.Azure.Documents.JsonSerializable.LoadFromWithConstructor (stream, constructorFunction, settings)" />
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
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="constructorFunction" Type="System.Func&lt;T&gt;" />
        <Parameter Name="settings" Type="Newtonsoft.Json.JsonSerializerSettings" />
      </Parameters>
      <Docs>
        <typeparam name="T">オブジェクトの型。</typeparam>
        <param name="stream">読み込むストリーム。</param>
        <param name="constructorFunction">返されるオブジェクトに使用されるコンス トラクターです。</param>
        <param name="settings">使用する JsonSerializerSettings。</param>
        <summary>
            Azure Cosmos DB サービスの特定のコンス トラクターを使用して、指定されたストリームを逆シリアル化します。
            </summary>
        <returns>オブジェクトは、指定したストリームから読み込まれます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveTo">
      <MemberSignature Language="C#" Value="public void SaveTo (System.IO.Stream stream, Microsoft.Azure.Documents.SerializationFormattingPolicy formattingPolicy = Microsoft.Azure.Documents.SerializationFormattingPolicy.None);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SaveTo(class System.IO.Stream stream, valuetype Microsoft.Azure.Documents.SerializationFormattingPolicy formattingPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.SaveTo(System.IO.Stream,Microsoft.Azure.Documents.SerializationFormattingPolicy)" />
      <MemberSignature Language="F#" Value="member this.SaveTo : System.IO.Stream * Microsoft.Azure.Documents.SerializationFormattingPolicy -&gt; unit" Usage="jsonSerializable.SaveTo (stream, formattingPolicy)" />
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
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="formattingPolicy" Type="Microsoft.Azure.Documents.SerializationFormattingPolicy" />
      </Parameters>
      <Docs>
        <param name="stream">この出力ストリームにオブジェクトを保存します。</param>
        <param name="formattingPolicy">シリアル化が省略可能であることをオブジェクトを保存するときに、ポリシーを書式設定を使用します。 既定のポリシーは、[なし] に設定されます。</param>
        <summary> 
            Cosmos DB の Azure サービスで指定したストリームにオブジェクトを保存します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveTo">
      <MemberSignature Language="C#" Value="public void SaveTo (System.IO.Stream stream, Microsoft.Azure.Documents.SerializationFormattingPolicy formattingPolicy, Newtonsoft.Json.JsonSerializerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SaveTo(class System.IO.Stream stream, valuetype Microsoft.Azure.Documents.SerializationFormattingPolicy formattingPolicy, class Newtonsoft.Json.JsonSerializerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.SaveTo(System.IO.Stream,Microsoft.Azure.Documents.SerializationFormattingPolicy,Newtonsoft.Json.JsonSerializerSettings)" />
      <MemberSignature Language="F#" Value="member this.SaveTo : System.IO.Stream * Microsoft.Azure.Documents.SerializationFormattingPolicy * Newtonsoft.Json.JsonSerializerSettings -&gt; unit" Usage="jsonSerializable.SaveTo (stream, formattingPolicy, settings)" />
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
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="formattingPolicy" Type="Microsoft.Azure.Documents.SerializationFormattingPolicy" />
        <Parameter Name="settings" Type="Newtonsoft.Json.JsonSerializerSettings" />
      </Parameters>
      <Docs>
        <param name="stream">この出力ストリームにオブジェクトを保存します。</param>
        <param name="formattingPolicy">オブジェクトを保存するときに、ポリシーを書式設定、カスタムのシリアル化を使用します。</param>
        <param name="settings">使用するシリアライザーの設定。</param>
        <summary> 
            Cosmos DB の Azure サービスで指定したストリームにオブジェクトを保存します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.JsonSerializable.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="jsonSerializable.ToString " />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Azure Cosmos DB サービスのオブジェクトの文字列表現を返します。
            </summary>
        <returns>オブジェクトの文字列表現。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>