<Type Name="CompositeTableKey" FullName="Microsoft.Azure.Mobile.Server.CompositeTableKey">
  <TypeSignature Language="C#" Value="public class CompositeTableKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CompositeTableKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />
  <TypeSignature Language="VB.NET" Value="Public Class CompositeTableKey" />
  <TypeSignature Language="F#" Value="type CompositeTableKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            A<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />テーブル内の単一行の識別に使用される 1 つまたは複数のキーが含まれています。
            文字列の形式、<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />必要に応じて 1 つの引用符で囲まれた用語の (LWS) なしのコンマ区切りリストです。
            コンマが含まれている場合に引用符で囲む、条項があるだけです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CompositeTableKey (params string[] segments);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] segments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray segments As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.CompositeTableKey : string[] -&gt; Microsoft.Azure.Mobile.Server.CompositeTableKey" Usage="new Microsoft.Azure.Mobile.Server.CompositeTableKey segments" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="segments" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="segments">順序付けされたセット<see cref="T:System.String" />セグメントを複合キーを作成します。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />で指定された数の<see cref="T:System.String" />複合キーを構成するセグメントの順序付きリストを表すです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parse">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.CompositeTableKey Parse (string tableKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.CompositeTableKey Parse(string tableKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.Parse(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Parse (tableKey As String) As CompositeTableKey" />
      <MemberSignature Language="F#" Value="static member Parse : string -&gt; Microsoft.Azure.Mobile.Server.CompositeTableKey" Usage="Microsoft.Azure.Mobile.Server.CompositeTableKey.Parse tableKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.CompositeTableKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableKey">複合キーを含む値です。</param>
        <summary>
            として文字列を解析する<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />です。 必要に応じて 1 つの引用符で囲まれた用語の (LWS) なしのコンマ区切りリストにするのには、値がします。
            値が有効でない場合、<see cref="T:System.ArgumentException" />がスローされます。
            </summary>
        <returns>新しい <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Segments">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;string&gt; Segments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;string&gt; Segments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.CompositeTableKey.Segments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Segments As Collection(Of String)" />
      <MemberSignature Language="F#" Value="member this.Segments : System.Collections.ObjectModel.Collection&lt;string&gt;" Usage="Microsoft.Azure.Mobile.Server.CompositeTableKey.Segments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、順序付けられた<see cref="T:System.Collections.ObjectModel.Collection`1" />セグメントの複合キーを構成するのです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="compositeTableKey.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            生成、<see cref="T:System.String" />複合キーの形式です。
            </summary>
        <returns>A<see cref="T:System.String" />複合キーの形式です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParse">
      <MemberSignature Language="C#" Value="public static bool TryParse (string tableKey, out Microsoft.Azure.Mobile.Server.CompositeTableKey compositeTableKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParse(string tableKey, [out] class Microsoft.Azure.Mobile.Server.CompositeTableKey&amp; compositeTableKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.TryParse(System.String,Microsoft.Azure.Mobile.Server.CompositeTableKey@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParse (tableKey As String, ByRef compositeTableKey As CompositeTableKey) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParse : string *  -&gt; bool" Usage="Microsoft.Azure.Mobile.Server.CompositeTableKey.TryParse (tableKey, compositeTableKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableKey" Type="System.String" />
        <Parameter Name="compositeTableKey" Type="Microsoft.Azure.Mobile.Server.CompositeTableKey&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="tableKey">複合キーを含む値です。</param>
        <param name="compositeTableKey">メソッドを返す場合<c>true</c>し<paramref name="compositeTableKey" />結果を含むです。 それ以外の場合<c>null</c>です。</param>
        <summary>
            新たに作成する試行<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />から、指定された<paramref name="tableKey" />です。
            戻り値は、かどうか、解析が成功したことを示します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>