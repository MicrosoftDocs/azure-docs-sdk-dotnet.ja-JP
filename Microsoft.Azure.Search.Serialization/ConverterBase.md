<Type Name="ConverterBase" FullName="Microsoft.Azure.Search.Serialization.ConverterBase">
  <TypeSignature Language="C#" Value="public abstract class ConverterBase : Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConverterBase extends Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Serialization.ConverterBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConverterBase&#xA;Inherits JsonConverter" />
  <TypeSignature Language="F#" Value="type ConverterBase = class&#xA;    inherit JsonConverter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.JsonConverter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            カスタム JsonConverters の基本クラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ConverterBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Advance">
      <MemberSignature Language="C#" Value="protected void Advance (Newtonsoft.Json.JsonReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Advance(class Newtonsoft.Json.JsonReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Advance(Newtonsoft.Json.JsonReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Advance (reader As JsonReader)" />
      <MemberSignature Language="F#" Value="member this.Advance : Newtonsoft.Json.JsonReader -&gt; unit" Usage="converterBase.Advance reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
      </Parameters>
      <Docs>
        <param name="reader">進める JSON リーダーです。</param>
        <summary>
            指定した JSON リーダーを進めます。 またはそのできない高度な場合は、JsonSerializationException をスローします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expect">
      <MemberSignature Language="C#" Value="protected void Expect (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Expect(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Expect(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Expect (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null)" />
      <MemberSignature Language="F#" Value="member this.Expect : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; unit" Usage="converterBase.Expect (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="reader">JSON リーダーです。</param>
        <param name="expectedToken">リーダーが配置される予定 JSON トークンです。</param>
        <param name="expectedValue">省略可能です。現在の JSON トークンの予期される値。</param>
        <summary>
            予期された型、トークンに指定した JSON リーダーが配置されていることをアサートします。 必要に応じて、トークンの値が、指定された予想値と一致することをアサートします。 アサーションの失敗した場合、このメソッドは、JsonSerializationException をスローします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expect&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="protected TValue Expect&lt;TValue&gt; (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TValue Expect&lt;TValue&gt;(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Expect``1(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Function Expect(Of TValue) (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null) As TValue" />
      <MemberSignature Language="F#" Value="member this.Expect : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; 'Value" Usage="converterBase.Expect (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TValue">現在の JSON トークンの値の型。</typeparam>
        <param name="reader">JSON リーダーです。</param>
        <param name="expectedToken">リーダーが配置される予定 JSON トークンです。</param>
        <param name="expectedValue">省略可能です。現在の JSON トークンの予期される値。</param>
        <summary>
            存在する場合は、指定した JSON リーダーが配置されているトークンに予期された型と、トークンの値を取得ことをアサートします。 必要に応じて、トークンの値が、指定された予想値と一致することをアサートします。 アサーションの失敗した場合、このメソッドは、JsonSerializationException をスローします。
            </summary>
        <returns>
            現在の JSON トークン、または default(TValue) 現在のトークンに値が存在しない場合の値。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpectAndAdvance">
      <MemberSignature Language="C#" Value="protected void ExpectAndAdvance (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ExpectAndAdvance(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.ExpectAndAdvance(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ExpectAndAdvance (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null)" />
      <MemberSignature Language="F#" Value="member this.ExpectAndAdvance : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; unit" Usage="converterBase.ExpectAndAdvance (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="reader">JSON リーダーです。</param>
        <param name="expectedToken">リーダーが配置される予定 JSON トークンです。</param>
        <param name="expectedValue">省略可能です。現在の JSON トークンの予期される値。</param>
        <summary>
            予期された型、トークンに指定した JSON リーダーが配置されていることをアサートします。 必要に応じて、トークンの値が、指定された予想値と一致することをアサートします。 アサーションの失敗した場合、このメソッドは、JsonSerializationException をスローします。 それ以外の場合、このメソッドは、JSON リーダーの次の位置を進めしようとします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpectAndAdvance&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="protected TValue ExpectAndAdvance&lt;TValue&gt; (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TValue ExpectAndAdvance&lt;TValue&gt;(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.ExpectAndAdvance``1(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Function ExpectAndAdvance(Of TValue) (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null) As TValue" />
      <MemberSignature Language="F#" Value="member this.ExpectAndAdvance : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; 'Value" Usage="converterBase.ExpectAndAdvance (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TValue">現在の JSON トークンの値の型。</typeparam>
        <param name="reader">JSON リーダーです。</param>
        <param name="expectedToken">リーダーが配置される予定 JSON トークンです。</param>
        <param name="expectedValue">省略可能です。現在の JSON トークンの予期される値。</param>
        <summary>
            存在する場合は、指定した JSON リーダーが配置されているトークンに予期された型と、トークンの値を取得ことをアサートします。 必要に応じて、トークンの値が、指定された予想値と一致することをアサートします。 アサーションの失敗した場合、このメソッドは、JsonSerializationException をスローします。 それ以外の場合、このメソッドは、JSON リーダーの次の位置を進めしようとします。
            </summary>
        <returns>
            トークンに値が存在しない場合は、reader、または default(TValue) を進める前に、JSON トークンの値。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>