<Type Name="RelayConnectionStringBuilder" FullName="Microsoft.Azure.Relay.RelayConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class RelayConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RelayConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type RelayConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            作成し、接続文字列の内容を管理します。 このクラスは、リレーの名前空間を操作するための接続文字列を構築するために使用できます。 既存の接続文字列で基本的な検証を実行するも使用できます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayConnectionStringBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayConnectionStringBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.RelayConnectionStringBuilder : string -&gt; Microsoft.Azure.Relay.RelayConnectionStringBuilder" Usage="new Microsoft.Azure.Relay.RelayConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">接続文字列、Azure 管理ポータルから取得できます。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" />指定した既存の接続文字列にします。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">ConnectionString が null または空の場合にスローされます。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
            場合にスロー<see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />は正数でない<see cref="T:System.TimeSpan" />です。
            </exception>
        <exception cref="T:System.ArgumentException">
            キーまたは値のいずれか、キー値のペアがない場合にスローされます。
            場合にスロー<see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" />が指定されているが、有効な絶対パスではない<see cref="T:System.Uri" />です。
            場合にスロー<see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />が指定されているが、有効ではありません<see cref="T:System.TimeSpan" />形式です。
            サポートされていないキー名が指定されている場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public Uri Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.Endpoint : Uri with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレーの名前空間アドレスを設定します。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">エンドポイントが設定されている場合にスローされますを null にします。</exception>
        <exception cref="T:System.ArgumentException">エンドポイント設定されている場合にスローされます、<see cref="T:System.Uri" />絶対ではないです。</exception>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、HybridConnection のエンティティのパスを設定します。</summary>
        <value>エンティティのパスを返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定、<see cref="T:System.TimeSpan" />操作がタイムアウトするまでに完了する必要がある期間を指定します。</summary>
        <value>操作がタイムアウトまでに完了する必要がある時間を指定する <see cref="T:System.TimeSpan" />。既定値は、1 分です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">OperationTimeout が正数でない時間帯に設定されている場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKey">
      <MemberSignature Language="C#" Value="public string SharedAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKey : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または接続の認証用の共有アクセス キーを設定します。</summary>
        <value>接続の認証用の共有アクセス キー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyName">
      <MemberSignature Language="C#" Value="public string SharedAccessKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKeyName : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または共有アクセス キーの名前を設定します。</summary>
        <value>共有アクセス キーの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または SAS トークンを設定します。</summary>
        <value>構成された SAS トークンを返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="relayConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在のオブジェクトを表す接続文字列を作成します。</summary>
        <returns>現在のオブジェクトを表す接続文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>