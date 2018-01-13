<Type Name="GetPageDiffRangesResponse" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse">
  <TypeSignature Language="C#" Value="public sealed class GetPageDiffRangesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GetPageDiffRangesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GetPageDiffRangesResponse&#xA;Inherits ResponseParsingBase(Of PageDiffRange)" />
  <TypeSignature Language="F#" Value="type GetPageDiffRangesResponse = class&#xA;    inherit ResponseParsingBase&lt;PageDiffRange&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.Blob.PageDiffRange</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ページ blob の異なるページの範囲を取得するための操作からの応答を解析するためのメソッドを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetPageDiffRangesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse" Usage="new Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse stream" />
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
        <param name="stream">解析するページ範囲のストリーム。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageRangesResponse" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PageDiffRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; PageDiffRanges { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; PageDiffRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse.PageDiffRanges" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PageDiffRanges As IEnumerable(Of PageDiffRange)" />
      <MemberSignature Language="F#" Value="member this.PageDiffRanges : seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse.PageDiffRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            列挙可能なコレクションを取得<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />応答からのオブジェクト。
            </summary>
        <value>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of PageDiffRange)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" Usage="getPageDiffRangesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ページ blob のページの範囲を取得するための操作に対する XML 応答を解析します。
            </summary>
        <returns>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>