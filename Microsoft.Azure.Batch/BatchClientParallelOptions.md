<Type Name="BatchClientParallelOptions" FullName="Microsoft.Azure.Batch.BatchClientParallelOptions">
  <TypeSignature Language="C#" Value="public class BatchClientParallelOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchClientParallelOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchClientParallelOptions" />
  <TypeSignature Language="F#" Value="type BatchClientParallelOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クライアント並列操作のバッチでメソッドの操作を構成するオプションを格納します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchClientParallelOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClientParallelOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancellationToken">
      <MemberSignature Language="C#" Value="public System.Threading.CancellationToken CancellationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Threading.CancellationToken CancellationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClientParallelOptions.CancellationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property CancellationToken As CancellationToken" />
      <MemberSignature Language="F#" Value="member this.CancellationToken : System.Threading.CancellationToken with get, set" Usage="Microsoft.Azure.Batch.BatchClientParallelOptions.CancellationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.CancellationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="T:System.Threading.CancellationToken" />これに関連付けられている<see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />インスタンス。
            既定では、 <see cref="P:System.Threading.CancellationToken.None" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public int MaxDegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClientParallelOptions.MaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelism As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelism : int with get, set" Usage="Microsoft.Azure.Batch.BatchClientParallelOptions.MaxDegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            これによって有効になっている同時実行タスクの最大数を取得または<see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />インスタンス。
            既定値は 1 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>