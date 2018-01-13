<Type Name="UploadChunkRange" FullName="System.Fabric.Query.UploadChunkRange">
  <TypeSignature Language="C#" Value="public sealed class UploadChunkRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UploadChunkRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.UploadChunkRange" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UploadChunkRange" />
  <TypeSignature Language="F#" Value="type UploadChunkRange = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            UploadChunkRange 含む開始および終了バイトのチャンクの位置
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EndPosition">
      <MemberSignature Language="C#" Value="public long EndPosition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EndPosition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadChunkRange.EndPosition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndPosition As Long" />
      <MemberSignature Language="F#" Value="member this.EndPosition : int64" Usage="System.Fabric.Query.UploadChunkRange.EndPosition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得は、ファイル アップロードからバイトのチャンクの位置を終了します。</para>
        </summary>
        <value>
          <para>バイトのチャンクの終了位置。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartPosition">
      <MemberSignature Language="C#" Value="public long StartPosition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StartPosition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadChunkRange.StartPosition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartPosition As Long" />
      <MemberSignature Language="F#" Value="member this.StartPosition : int64" Usage="System.Fabric.Query.UploadChunkRange.StartPosition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アップロード ファイルからバイトのチャンクの開始位置を取得します。</para>
        </summary>
        <value>
          <para>バイトのチャンクの開始位置。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>