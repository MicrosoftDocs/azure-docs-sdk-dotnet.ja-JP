<Type Name="ServiceTypeHealthPolicy" FullName="System.Fabric.Health.ServiceTypeHealthPolicy">
  <TypeSignature Language="C#" Value="public class ServiceTypeHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceTypeHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceTypeHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceTypeHealthPolicy" />
  <TypeSignature Language="F#" Value="type ServiceTypeHealthPolicy = class" />
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
      <para>サービスの種類に属するサービスの正常性を評価するために使用する正常性ポリシーを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceTypeHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceTypeHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>既定では、エラーまたは警告が許容されません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyPartitionsPerService">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyPartitionsPerService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyPartitionsPerService As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyPartitionsPerService : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyPartitionsPerService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはサービスごとの問題のあるパーティションの最大許容パーセンテージを設定します。</para>
        </summary>
        <value>
          <para>許容されるサービスごとの問題のあるパーティションの割合の最大値を返します。
            使用できる値は<see cref="T:System.Byte" />0 から 100 までの値。</para>
        </value>
        <remarks>
          <para>
            パーセンテージは、パーティションことのできる正常な状態、サービスがエラーと見なされるまでの最大許容パーセンテージを表します。 割合が守られて異常な場合に、少なくとも 1 つのパーティションがある場合は、正常性は警告として評価されます。
            これは、サービスのパーティションの総数に対して異常なパーティションの数で割ることによって計算されます。
            計算は、パーティション数が少ないで 1 つの障害を許容するように丸めます。 既定のパーセンテージは 0 です。
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyReplicasPerPartition">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyReplicasPerPartition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyReplicasPerPartition" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyReplicasPerPartition As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyReplicasPerPartition : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyReplicasPerPartition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定パーティションあたりの異常なレプリカの最大許容パーセンテージです。</para>
        </summary>
        <value>
          <para>許容される異常なレプリカ パーティションあたりの割合の最大値を返します。
            使用できる値は<see cref="T:System.Byte" />0 から 100 までの値。</para>
        </value>
        <remarks>
          <para>
            パーセンテージは、ことのできる正常なエラーでは、パーティションは考慮する前にレプリカの最大許容パーセンテージを表します。 割合が守られて異常な場合に、少なくとも 1 つのレプリカがある場合は、正常性は警告として評価されます。
            これは、パーティション内のレプリカの合計数に問題があるレプリカの数で割ることによって計算されます。
            計算は、少数のレプリカの 1 つの障害を許容するように丸めます。 既定のパーセンテージは 0 です。
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyServices">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyServices" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyServices" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyServices As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyServices : byte with get, set" Usage="System.Fabric.Health.ServiceTypeHealthPolicy.MaxPercentUnhealthyServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または異常なサービスの最大許容パーセンテージを設定します。</para>
        </summary>
        <value>
          <para>許容される異常なサービスの割合の最大値を返します。 使用できる値は<see cref="T:System.Byte" />0 から 100 までの値。</para>
        </value>
        <remarks>
          <para>
            パーセンテージは、サービスことのできる正常なアプリケーションがエラーと見なされるまでの最大許容パーセンテージを表します。 割合が守られて異常な場合に、少なくとも 1 つのサービスがある場合は、正常性は警告として評価されます。
            これは、特定のサービス型のサービスの合計数を特定のサービスの種類の問題のあるサービスの数で割ることによって計算されます。
            計算は、少数のサービスの 1 つの障害を許容するように丸めます。 既定のパーセンテージは 0 です。
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceTypeHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceTypeHealthPolicy.ToString " />
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
            サービスの種類の正常性ポリシーの文字列表現を取得します。
            </summary>
        <returns>サービスの種類の正常性ポリシーの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>