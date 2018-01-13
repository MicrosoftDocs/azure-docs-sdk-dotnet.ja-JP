<Type Name="ListRangesResponse" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse">
  <TypeSignature Language="C#" Value="public sealed class ListRangesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListRangesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.File.FileRange&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListRangesResponse&#xA;Inherits ResponseParsingBase(Of FileRange)" />
  <TypeSignature Language="F#" Value="type ListRangesResponse = class&#xA;    inherit ResponseParsingBase&lt;FileRange&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.File.FileRange</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ファイルの範囲を取得するための操作からの応答を解析するためのメソッドを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListRangesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse" Usage="new Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse stream" />
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
        <param name="stream">解析する範囲のストリーム。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.FileRange&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of FileRange)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;" Usage="listRangesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            操作がファイルの範囲を取得する XML 応答を解析します。
            </summary>
        <returns>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ranges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt; Ranges { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.FileRange&gt; Ranges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse.Ranges" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Ranges As IEnumerable(Of FileRange)" />
      <MemberSignature Language="F#" Value="member this.Ranges : seq&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse.Ranges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            列挙可能なコレクションを取得<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" />応答からのオブジェクト。
            </summary>
        <value>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" />オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>