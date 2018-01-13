<Type Name="LatencyTracker" FullName="Microsoft.Azure.DataLake.Store.LatencyTracker">
  <TypeSignature Language="C#" Value="public class LatencyTracker" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LatencyTracker extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.LatencyTracker" />
  <TypeSignature Language="VB.NET" Value="Public Class LatencyTracker" />
  <TypeSignature Language="F#" Value="type LatencyTracker = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             1 つのエントリ、コンマで区切って:
                  1. クライアント要求 ID
                  2. 待機時間 (ミリ秒単位)
                  3. エラー コード (要求が失敗しました)
                  4. 操作
                  5. 要求と応答本文のサイズ (使用できる場合は 0 それ以外の場合)
                  6. ADLStoreClient (この VM のインスタンスごとの一意な番号) のインスタンス
            
                 複数のエントリは、1 つの要求で指定できます。エントリは、HTTP 要求のサイズが増加するを制限する 1 つの要求を 3 つのエントリを最大の制限をセミコロンで区切られます。
                 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LatencyTracker ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.LatencyTracker.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public static void Disable ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Disable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.LatencyTracker.Disable" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Disable ()" />
      <MemberSignature Language="F#" Value="static member Disable : unit -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.LatencyTracker.Disable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            待機時間の追跡ツールを無効になります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>