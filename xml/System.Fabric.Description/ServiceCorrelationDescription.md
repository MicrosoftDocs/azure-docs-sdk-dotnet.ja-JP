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
      <para><span data-ttu-id="abdd7-101">サービス間の特定の相関関係を作成します。</span><span class="sxs-lookup"><span data-stu-id="abdd7-101">Creates a particular correlation between services.</span></span></para>
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
          <para><span data-ttu-id="abdd7-102"><see cref="T:System.Fabric.Description.ServiceCorrelationDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="abdd7-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceCorrelationDescription" /> class.</span></span></para>
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
          <para><span data-ttu-id="abdd7-103">取得または設定、<see cref="T:System.Fabric.Description.ServiceCorrelationScheme" />このサービスとで指定したサービス間のリレーションシップを記述する<see cref="P:System.Fabric.Description.ServiceCorrelationDescription.ServiceName" />です。</span><span class="sxs-lookup"><span data-stu-id="abdd7-103">Gets or sets the <see cref="T:System.Fabric.Description.ServiceCorrelationScheme" /> which describes the relationship between this service and the service specified via <see cref="P:System.Fabric.Description.ServiceCorrelationDescription.ServiceName" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="abdd7-104">サービスの相関関係スキームです。</span><span class="sxs-lookup"><span data-stu-id="abdd7-104">The service correlation scheme.</span></span></para>
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
          <para><span data-ttu-id="abdd7-105">取得またはとの相関関係を確立する場合、サービスの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="abdd7-105">Gets or sets the name of the service that you want to establish the correlation relationship with.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="abdd7-106">相関関係を確立するサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="abdd7-106">The name of the service that you want to establish the correlation relationship with.</span></span></para>
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
            <span data-ttu-id="abdd7-107">'ServiceName'、'スキーム' の形式で、ServiceCorrelationDescription の文字列を返します</span><span class="sxs-lookup"><span data-stu-id="abdd7-107">Returns a string of the ServiceCorrelationDescription in the form 'ServiceName', 'Scheme'</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="abdd7-108">ServiceCorrelationDescription オブジェクトを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="abdd7-108">A string representing the ServiceCorrelationDescription object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>