<Type Name="ServiceCorrelationDescription" FullName="System.Fabric.Description.ServiceCorrelationDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceCorrelationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceCorrelationDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceCorrelationDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceCorrelationDescription" />
  <TypeSignature Language="F#" Value="type ServiceCorrelationDescription = class" />
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
      <para>サービス間の特定の相関関係を作成します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceCorrelationDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceCorrelationDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServiceCorrelationDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceCorrelationScheme Scheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServiceCorrelationScheme Scheme" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceCorrelationDescription.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Property Scheme As ServiceCorrelationScheme" />
      <MemberSignature Language="F#" Value="member this.Scheme : System.Fabric.Description.ServiceCorrelationScheme with get, set" Usage="System.Fabric.Description.ServiceCorrelationDescription.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定、<see cref="T:System.Fabric.Description.ServiceCorrelationScheme" />このサービスとで指定したサービス間のリレーションシップを記述する<see cref="P:System.Fabric.Description.ServiceCorrelationDescription.ServiceName" />です。</para>
        </summary>
        <value>
          <para>サービスの相関関係スキームです。</para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceCorrelationDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri with get, set" Usage="System.Fabric.Description.ServiceCorrelationDescription.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはとの相関関係を確立する場合、サービスの名前を設定します。</para>
        </summary>
        <value>
          <para>相関関係を確立するサービスの名前。</para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceCorrelationDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceCorrelationDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para> 
            'ServiceName'、'スキーム' の形式で、ServiceCorrelationDescription の文字列を返します
            </para>
        </summary>
        <returns>
          <para>ServiceCorrelationDescription オブジェクトを表す文字列。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>